pipeline{
    agent any
    tools{
        maven 'Maven'
    }
    stages{
        stage("Maven Build"){
            steps{
                bat 'mvn clean package'
            }
        }
    }
}