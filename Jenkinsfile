pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building Project"'
            }
        }
        stage('Running Test') {
            steps {
                sh 'echo "Running test"'
            }
        }
    }    
    post {
        succes {
            echo "This pipeline succeeded"
        }

        failure {
            echo "Pipeline failed"
        }
    }

}
