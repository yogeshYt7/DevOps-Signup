pipeline {
    agent any
    tools{
        maven 'maven'
    }
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/yogeshYt7/DevOps-Signup.git'
            }
        }
        stage('validate') {
            steps {
                echo 'validation done'
            }
        }
        stage('compile') {
            steps {
                echo 'compilation done'
            }
        }
        stage('test') {
            steps {
                echo 'testing done'
            }
        }
        stage('package') {
            steps {
                echo 'bulid done'
            }
        }
        stage('verify') {
            steps {
                echo 'verification done'
            }
        }
        stage('install') {
            steps {
                echo 'installation done'
            }
        }
    }
}
