pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                sh '''
                    D:
                    cd tools/apache/bin
                    jmeter -n -t TestCase01.jmx -l Report4.jtl
                '''
            }
        }
    }
}

