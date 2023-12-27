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
            build(job: 'build', quietPeriod: 1)
          }
        }

      }
    }

  }
}
