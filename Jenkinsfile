pipeline {
  agent {
    node {
      label 'dev2'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        echo 'testing'
        emailext(subject: 'test', body: 'test', attachLog: true, from: 'test', mimeType: 'test', postsendScript: 'test', presendScript: 'test', replyTo: 'test', to: 'test')
      }
    }
  }
}