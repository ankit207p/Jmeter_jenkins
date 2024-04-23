pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                D:
                cd tools/apache-jmeter-5.6.3
                jmeter -n -t TestCase01.jmx -l Report4.jtl
                }
        }
    }
}
