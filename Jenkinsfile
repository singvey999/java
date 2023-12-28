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
        sh 'hostname;mvn -B -DskipTests clean package'
      }
    }

  }
}
