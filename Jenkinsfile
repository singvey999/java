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
<<<<<<< HEAD
        sh 'mvn -B -DskipTests clean package'
=======
        sh 'whoami;hostname;pwd'
>>>>>>> 91300c80fc8d7dc41d02c61a9aff9b267ca6a4ff
      }
    }

  }
}
