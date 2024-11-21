pipeline {
    agent any  // Use any available agent to run this pipeline

    stages {
        stage('Build') {
            steps {
                echo 'Build Hello, World!'  // This will print "Hello, World!" in the Jenkins log
            }
        }
         stage('Test') {
            steps {
                echo 'Testing Hello, World!'  // This will print "Hello, World!" in the Jenkins log
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Hello, World!'  // This will print "Hello, World!" in the Jenkins log
            }
        }
    }

    post {
        always {
            echo 'This will always run, no matter if the build succeeds or fails.'
        }
    }
}
