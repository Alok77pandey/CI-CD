pipeline {
  agent any
  
  stages {
    stage( 'print') {
      steps {
        echo " WELCOME TO THE WEBSITE"
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
