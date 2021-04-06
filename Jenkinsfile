pipeline {
    agent { label 'docker-agent' } 
    stages {
        stage('Clone source code') {
            steps {
                git 'https://github.com/mranh1610/demo-jenkin2.git'
            }
        }
    }
}
