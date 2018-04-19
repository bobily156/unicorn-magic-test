pipeline {
  agent any
  libraries {
    lib("SharedLibs")
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${params.Name}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  stage('Shared Lib') {
    steps {
      helloWorld("Jenkins")
    }
  }
}
