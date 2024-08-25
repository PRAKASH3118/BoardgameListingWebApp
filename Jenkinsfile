pipeline {
    agent any
     
    tools {
        maven 'maven3'
    }

    stages {        
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }


    }
}
