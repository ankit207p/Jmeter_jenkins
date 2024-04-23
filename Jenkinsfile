pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                bat 'jmeter -n -t TestCase01.jmx -l Report4.jtl'
            }
        }
    }
}

