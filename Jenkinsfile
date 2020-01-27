pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'Hello world'
          }
        }

        stage('Lint HTML') {
          steps {
            sh 'tidy-q-e *.html'
          }
        }

      }
    }

  }
}