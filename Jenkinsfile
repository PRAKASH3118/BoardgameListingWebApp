pipeline {
    agent any
    
    tools {
        maven 'maven3'
        jdk 'jdk17'
    }

    stages {        
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }


    }
}
