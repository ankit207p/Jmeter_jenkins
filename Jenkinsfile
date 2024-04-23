pipeline {
    agent any
    stages {
        stage('STAGE 1') {
            steps {
                sh '''
                    D:
                    cd D:\Tools\apache-jmeter-5.5\bin
                    jmeter -n -t D:\Tools\apache-jmeter-5.5\bin\TestCase01.jmx -l D:\Jenkin_Jemeter\Reports\Report4.jtl
                '''
            }
        }
    }
}

