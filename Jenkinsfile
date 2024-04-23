pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                bat '''
                    copy TestCase01.jmx C:/apache/bin
                    cd C:/Users/anshul.guleria/tools/apache/bin
                    dir .
                '''
            }
        }
    }
}

