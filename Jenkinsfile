pipeline{
    agent any

    stages{
        stage("Installing dependencies"){
            steps{
                bat 'npm install'
            }
        }
        stage("Test"){
            steps{
                bat 'npm test'
            }
        }
    }
}
