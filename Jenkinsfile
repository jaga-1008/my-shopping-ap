pipeline{
    agent any
    stages{
        stage('deploy test'){
            steps{
                echo "deploy to test environment"
            }
        }
        stage('call selenium job'){
            steps{
                build 'selenium-job'
            }
        }
    }
}
