pipeline {
  agent {
    node {
      label 'hostname=jumpsvr'
    }

  }
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'echo \'test\''
          }
        }

        stage('build') {
          steps {
            sh 'echo \'build\''
          }
        }

      }
    }

  }
}
