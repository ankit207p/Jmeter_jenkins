pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                D:
                cd D:/Tools/apache-jmeter-5.5/bin
                jmeter -n -t TestCase01.jmx -l Report4.jtl
                }
        }
    }
}
