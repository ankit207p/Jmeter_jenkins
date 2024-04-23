pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                bat '''
                    copy TestCase01.jmx /tools/apache/bin
                    cd /tools/apache/bin
                    dir .
                '''
            }
        }
    }
}

