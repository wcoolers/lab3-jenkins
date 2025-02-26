pipeline {
    agent any

    stages {
        stage('Task 1: Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/wcoolers/lab3-jenkins.git'
            }
        }

        stage('Task 2: Print date') {
            steps {
                script {
                    sh 'bash -c "echo Running Task 2: Today is $(date)"'
                }
            }
        }
    }
}
