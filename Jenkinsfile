pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                D:
                cd tools/apache/bin
                dir
                jmeter -n -t D:\tools\apache\binTestCase01.jmx -l Report4.jtl
                }
        }
    }
}
