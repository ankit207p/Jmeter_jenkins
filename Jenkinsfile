pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                D:
                cd D:\Tools\apache-jmeter-5.5\bin
                jmeter -n -t D:\Tools\apache-jmeter-5.5\bin\TestCase01.jmx -l D:\Jenkin_Jemeter\Reports\Report4.jtl
            }
        }
    }
}
