pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/Bhumikams/JenkinsDemo.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }

    }
}
