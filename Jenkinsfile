pipeline {
  agent any
  stages {
    stage('create location') {
      steps {
        ws(dir: 'Test123')
      }
    }
    stage('run script') {
      steps {
        echo 'do something'
      }
    }
    stage('send email') {
      steps {
        emailext(subject: 'test123', body: 'this is a test sent by JJ', from: 'j.jandu@jandusolutions.com', replyTo: 'j.jandu@jandusolutions.com', to: 'j.jandu@jandusolutions.com')
      }
    }
  }
}