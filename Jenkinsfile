pipeline {
    agent any
    tools {
        maven '3.8.7'
    }
    stages {
        stage ('Build Maven Project'){
            steps{
                bat 'mvn --version'
            }
        }
    }
}