pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                sh '''
                    echo "Checkout done - $PWD"
                    ls -l
                '''
            }
        }

        stage('Build the application') {
            steps {
                sh '''
                    echo "========== Building the Java Application =========="
                    mvn clean package
                    echo "=========== Building the Java Application completed ====="
                '''
            }
        }
    } // end of stages
} // end of pipeline

