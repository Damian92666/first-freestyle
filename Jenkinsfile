pipeline {
    agent any
    triggers { 
      pollSCM('* * * * *')
    }
    stages {
        stage('pull') {
            steps {
              git 'https://github.com/Damian92666/first-freestyle'
            }
        }
        stage('pollscm') {
            steps {
              sh 'cat README.md'
            }
        }
    }
}
