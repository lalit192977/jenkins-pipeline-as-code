pipeline{

agent any 

    stages{
        stage('SCM'){
            steps{
                echo "pull my code step 1"
                echo "pull my code step 2"
            }
        }

        stage('Deploy'){
            steps{
                echo "deploy my code"
            }
        }

        stage('Test'){
            steps{
                echo "test my code"
            }
        }
    }
}