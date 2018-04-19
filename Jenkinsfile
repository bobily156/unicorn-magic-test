pipeline {
  agent any
  libraries {
    lib("SharedLibs")
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello"
      }
    }
  }
  stage('Shared Lib') {
    steps {
      helloWorld("Jenkins")
    }
  }
}
