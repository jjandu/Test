pipeline {
  agent any
  stages {
    stage('run script') {
      steps {
        echo 'do something'
      }
    }
    stage('send email') {
      steps {
        mail(subject: 'test123', body: 'test123', from: 'j.jandu@jandusolutions.com', replyTo: 'j.jandu@jandusolutions.com', to: 'j.jandu@jandusolutions.com')
      }
    }
  }
}