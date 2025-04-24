pipeline {
    agent any
    environment {
        PATH = "/opt/maven/bin:$PATH"
    }
    stages { 
        stage('mybuild') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
