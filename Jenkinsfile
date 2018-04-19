pipeline {
  agent any
  stages {
    stage('Say hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Mack'
    TEST_USER = credentials('test-user')
  }
}