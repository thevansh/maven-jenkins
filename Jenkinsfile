pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/thevansh/maven-jenkins.git'
            }
        }
        
        stage('test build'){
            steps{
                echo 'building test pipeline'
            }
        }
        stage('qa build'){
            steps{
                echo 'building qa pipeline'
            }
        }
        
    }
}
