~pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                script {
                    // Single-line example
                    sh 'echo "Hello from Stage 1" >> 
output.txt'
                }
            }
        }
        stage('Stage 2') {
            steps {
                script {
                    // Single-line example
                    sh 'echo "Hello from Stage 2" >> 
output.txt'
                }
            }
        }
        stage('Stage 3') {
            steps {
                script {
                    // Multi-line example
                    sh '''
                    echo "Hello from Stage 3 - line 1" >> 
output.txt
                    echo "Hello from Stage 3 - line 2" >> 
output.txt
                    '''
                }
            }
        }
    }
}
~
