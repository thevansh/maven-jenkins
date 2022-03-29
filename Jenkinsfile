pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/thevansh/maven-jenkins.git'
            }
        }
        
        stage('qa build'){
            steps{
                echo 'building qa pipeline'
            }
        }
        stage('prod build'){
            steps{
                echo 'building prod pipeline'
            }
        }
        
    }
}
