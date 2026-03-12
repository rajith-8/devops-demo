pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/rajith-8/devops-demo.git'
            }
        }

        stage('Run App') {
            steps {
                sh 'node app.js'
            }
        }

    }
}
