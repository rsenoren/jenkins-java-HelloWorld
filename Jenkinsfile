node {
    def app

    stage('Clone repository') {
      

        checkout scm
    }

    stage('Build image') {
  
       app = docker.build("Ronald/simplejavaapp")
    }

    stage('Test image') {
  
        docker.image('Ronald/simplejavaapp:latest').withRun() { c ->
            sh ' echo "tested" '
    }
        
    }
  
   
}
