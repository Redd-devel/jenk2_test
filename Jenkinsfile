pipeline {
    agent any
    environment {
        TEST_JENK2 = 'Test_jenk2'
    }
    stages {
        stage('Echo') {
            steps {
                git 'https://github.com/Redd-devel/jenk2_test.git'
                sh 'cat /usr/lib/os-release'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
