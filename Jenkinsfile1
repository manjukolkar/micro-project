pipeline{
    agent any
    stages{
        stage('Print server hostname'){
            steps{
                sh 'hostname'
            }
        }
        stage('Server uptime'){
            steps{
                sh 'uptime'
            }
        }
        stage('Server disk usage'){
            steps{
                sh 'df -h'
            }
        }
        stage('CPU details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Memory usage'){
            steps{
                sh 'free -h'
            }
        }
    }
}
