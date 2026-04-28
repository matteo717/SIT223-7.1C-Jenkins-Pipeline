pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Build stage: using Maven to compile and package the application"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Running unit tests with JUnit"
                echo "Running integration tests with Selenium"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Analyzing code quality using SonarQube"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Performing security scan using OWASP Dependency-Check"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Deploying application to staging server (AWS EC2)"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Running integration tests on staging environment"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Deploying application to production server (AWS EC2)"
            }
        }
    }
}