node {
    
    stage('Clone sources') {
        git url: 'https://github.com/eshanis/jenkins-java-HelloWorld.git'
    }
    
    stage('build') {
        sh 'javac HelloWorld.java'
        
    }

    stage('test') {
       sh 'java HelloWorld'
    }

    stage('deploy') {
        sh 'java HelloWorld'
   
    }

    
}
