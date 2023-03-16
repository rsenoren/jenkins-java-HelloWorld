node {
    def app

    stage('Clone repository') {
      

        checkout scm
    }

    stage('Build image') {
  
       app = docker.build("khadijeh/simplejavaapp")
    }

    stage('Test image') {
  
        docker.image('khadijeh/simplejavaapp:latest').withRun() { c ->
            sh ' echo "tested" '
    }
        
    }
  
   
}
