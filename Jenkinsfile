node {
    def app

    stage('Clone repository') {
      

        checkout scm
    }

    stage('Build image') {
  
       app = docker.build("laxmi/simplejavaapp")
    }

    stage('Test image') {
  
        docker.image('laxmi/simplejavaapp:latest').withRun() { c ->
            sh ' echo "tested" '
    }
        
    }
  
   
}
