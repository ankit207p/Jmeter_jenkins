pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                D:
                cd tools/apache/bin
                jmeter -n -t TestCase01.jmx -l Report4.jtl
                }
        }
    }
}
