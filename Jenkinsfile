pipeline {
    agent any
    
      environment {
          location="/home/ist/test/test/jenkins"
        branch = 'dev'
    }
   
    
    stages {
        stage('Build') {
            steps {
               sh "echo working $branch "
            }
        }
        stage('Test') {
            steps {
              sh "echo working "
            }
        }
        stage('Deploy') {
            steps {
               sh "echo working "
            }
        }
        stage('Docker') {
            steps {
                sh "echo working "
            }
        }
    }
}
