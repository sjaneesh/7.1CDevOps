pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Stage 1: Build - Building the code using Maven to compile and package the application'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests - Running unit tests using JUnit and integration tests using Selenium to ensure code functions correctly'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis - Analysing code using SonarQube to ensure it meets industry standards'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan - Performing security scan using OWASP ZAP to identify vulnerabilities'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging - Deploying application to staging server on AWS EC2 instance'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging - Running integration tests on staging environment to ensure application functions as expected'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production - Deploying application to production server on AWS EC2 instance'
            }
        }

    }
}
