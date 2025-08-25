pipeline {
    agent any
  
    stages{
        stage("Cloning from Github...."){
            steps{
                script{
                    echo 'Cloning from Github...'
                    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-token', url: 'https://github.com/manjudata/MLOPS-PROJECT-2-1.git']])
                }
            }
        }        
    }
}