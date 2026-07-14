pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...Avi '
                // Add build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...Oshi'
                // Add test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...Shashank'
                // Add deploy steps here
            }
        }
    }

    post {
        always {
            echo 'This will always run after the stages.'
        }
        success {
            echo 'This will run only if the pipeline succeeds.'
        }
        failure {
            echo 'This will run only if the pipeline fails.'
        }
    }
}
