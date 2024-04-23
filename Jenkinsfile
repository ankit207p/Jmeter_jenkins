pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                sh '''
                    D:
                    cd tools/apache/bin
                    jmeter -n -t tools/apache/bin/TestCase01.jmx -l /tools/apache/bin/Report4.jtl
                '''
            }
        }
    }
}

