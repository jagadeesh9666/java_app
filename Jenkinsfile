pipeline {
    agent any 
    stages {
        stage('Git checkout') { 
            steps {
                git branch: 'main',
                    url: 'https://github.com/jagadeesh9666/java_app.git'
            }
        }
    }
}