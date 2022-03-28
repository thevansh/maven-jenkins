pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/thevansh/maven-jenkins.git'
            }
        }
        
        stage('maven build'){
            steps{
                sh 'mvn package'
            }
        }
        stage('test build'){
            steps{
                echo 'building test pipeline'
            }
        }
        
    }
}
