pipeline {
  agent {
    node {
      label 'hostname=jumpsvr'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'echo \'test\''
      }
    }

    stage('build') {
      steps {
        sh 'whoami;hostname;pwd'
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}
