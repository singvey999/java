pipeline {
  agent {
    node {
      label 'hostname=jumpsvr'
    }
  }
  stages {
    stage('pull code') {
      steps {
        sh 'echo \'pull code\''
	echo 'task 02'
      }
    }
    stage('build code') {
      steps {
	echo 'build task 01'
      }
    }
    stage('deploy') {
      steps {
	echo 'deploy task 01'
      }
    }
  }
  post {
    always {
      echo "last task"
    }
  }
}
