pipeline{
    agent any

    stages{
        stage('Server Hostname'){
            steps{
                sh 'hostname'
            }
        }
        stage('Server Uptime'){
            steps{
                sh 'uptime'
            }
        }
        stage('Server Disk Usage'){
            steps{
                sh 'df -h'
            }
        }
        stage('Cpu Details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Memory Usage'){
            steps{
                sh 'free -h'
            }
        }
        stage('Drives'){
            steps{
                sh 'lsblk'
            }
        }
    }
}
