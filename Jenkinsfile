pipeline {
  agent any
  
  stages {
    stage( 'print') {
      steps {
        sh "index.html"
      }
    }
  }
  post {
    always {
      echo ' REDIRECT '
    }
    success {
      echo ' SUCCESSFULLY ACCESSED THE SITE '
    }
    failure{
      echo ' ACCESS FAILED '
    }
  }
}
