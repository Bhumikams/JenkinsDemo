pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/Bhumikams/JenkinsDemo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building Project..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing Application..."'
            }
        }

        stage('Run Script') {
            steps {
                sh 'bash script.sh'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deployment Completed"'
            }
        }

    }
}
