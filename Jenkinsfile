pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                bat '''
                    dir .
                    move TestCase01.jmx D:/temp
                    copy D:/temp/TestCase01.jmx C:/apache/bin
                    cd C:/apache/bin
                    dir .
                '''
            }
        }
    }
}

