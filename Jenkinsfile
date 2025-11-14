library identifier: 'jenkins-shared-library@main',
        retriever: modernSCM([$class: 'GitSCMSource', remote: 'https://github.com/VJ-CCS-Tech-ops/former-emp.git'])

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                audit()
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... the test'
            }
        }
    }
}