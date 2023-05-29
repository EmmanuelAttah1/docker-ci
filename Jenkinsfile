pipeline{
    agent {
        node{
            label 'docker-agent-python'
        }
    }
    stages{
        stage('testing'){
            steps{
                echo "testing software"
            }
        }
        stage('building'){
            steps{
                echo 'Building software'
            }
        }
        stage("deploying"){
            steps{
                echo "Deploying to live server oooo"
            }
        }
        stage("clean up"){
            steps{
                echo "Cleaning up"
            }
        }
    }
}