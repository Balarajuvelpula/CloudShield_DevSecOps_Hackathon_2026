pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Balarajuvelpula/CloudShield_DevSecOps_Hackathon_2026.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build stage"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploy stage"'
            }
        }
    }
}
