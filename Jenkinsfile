library identifier: 'jenkins-shared-library@main',
        retriever: modernSCM([$class: 'GitSCMSource', remote: 'git@github.com:VJ-CCS-Tech-ops/jenkins-shared-library.git'])

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