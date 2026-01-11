pipeline {
    agent any

    stages {
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

