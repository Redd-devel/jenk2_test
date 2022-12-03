pipeline {
    agent any
    stages {
        stage('Echo') {
            steps {
                echo "Pipeline"
            }
        }
    }
    post {
        always {
            cleanWS()
        }
    }
}