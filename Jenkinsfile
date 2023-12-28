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
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}
