pipeline {
  agent any

  stages {
    stage('Hello') {
      steps {
        sh 'echo Helo'
        sh 'echo Bye'
        print 'Hello'
        script {
          println "Hello World"
        }
      }
    }

  }

  post {
    always {
      println 'Post step'
    }
  }

}

