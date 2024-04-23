pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                bat '''
                    dir .
                    copy TestCase01.jmx C:/apache/bin/
                    cd C:/apache/bin
                    dir .
                '''
            }
        }
    }
}

