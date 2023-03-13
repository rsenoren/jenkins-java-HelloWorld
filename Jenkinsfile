node {
    def app

    stage('build') {
        sh 'git pull https://github.com/eshnil2000/jenkins-java-HelloWorld'
        sh 'javac HelloWorld.java'
        
    }

    stage('test') {
       sh 'git pull https://github.com/eshnil2000/jenkins-java-HelloWorld'
       sh 'java HelloWorld'
    }

    stage('deploy') {
        sh 'git pull https://github.com/eshnil2000/jenkins-java-HelloWorld'
        sh 'java HelloWorld'
   
    }

    
}
