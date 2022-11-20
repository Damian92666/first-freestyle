pipeline {
    agent any
    triggers { 
      pollSCM('* * * * *')
    }
    stages {
        stage('pollscm') {
            steps {
              sh 'cat README.md'
              echo "hello"
            }
        }
    }
}
