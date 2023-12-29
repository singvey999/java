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
  
  }
}
