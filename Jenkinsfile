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
	//test
      }
      steps {
        sh 'echo \'step 02\''
      }
    }
  
  }
}
