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
        sh 'source /etc/profile.d/maven.sh;mvn -B -DskipTests clean package'
      }
    }

  }
}
