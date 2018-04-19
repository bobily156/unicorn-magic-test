pipeline {
  agent any
  stages {
    stage('Say hello to my lil friend') {
      steps {
        sh '''pipeline {
 agent any
   stages {
      stage(\'Say hello to my lil friend\') {
         steps {
            echo \'Say hello to my lil friend! Now say goodbye\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }