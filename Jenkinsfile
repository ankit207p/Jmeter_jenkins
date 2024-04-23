pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                bat '''
                    copy TestCase01.jmx /tool/apache/bin
                    dir .
                '''
            }
        }
    }
}

