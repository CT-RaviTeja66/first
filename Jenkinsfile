pipeline {
    agent { label 'teja10.100.30.83' }
    stages {
        stage('Clone repository') {
            environment {
                GIT_SSH_COMMAND="ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no"
            }
            steps {
                dir('/home/teja/test1/') {
                    echo "started"
                    git branch: 'myrepo', credentialsId: 'teja', url: 'https://github.com/CT-RaviTeja66/first.git'
                    echo "completed"
                } 
            }
        }       
          stage('Build') {
            steps {

               sh """ 
               pwd
                  cp /home/teja/test1/* /home/teja/test2/
                """
            }
        }
        
        // Add more stages for your pipeline
        // ...
    }
}
