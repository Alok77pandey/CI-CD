pipeline {
  agent any
  
  triggers {
    cron('H/30 ****')
  }
  
  stages {
    stage( 'INDEX') {
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
