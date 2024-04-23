pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                D:
                cd tools/apache/bin
                jmeter -n -t D:/tools/apache/bin/TestCase01.jmx -l D:/tools/apache/bin/Report4.jtl
            }
        }
    }
}

