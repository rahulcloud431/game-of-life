pipeline {
    agent {label 'AZURE'}
    stages {
        stage('Source'){
            steps {
                git 'https://github.com/rahulcloud431/game-of-life.git' 
            }
        }
        stage('Package'){
            steps {
                sh 'mvn package'
            }
        }
    }
}
