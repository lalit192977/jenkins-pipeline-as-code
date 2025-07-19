pipeline{

agent any 

    stages{
        stage('SCM'){
            steps{
                echo "pull my code step 1"
                git 'https://github.com/lalit192977/simple-java-maven-app'
            }
        }

        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
        }

        stage('Deploy'){
            steps{
                sh "java -jar target/*.jar"
            }
        }

        stage('Deploy to prod'){
            steps{
                echo "final deployment"
            }
        }
    }
}