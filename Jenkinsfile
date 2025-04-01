pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'mvn build'
          }
        }

        stage('build02') {
          steps {
            sh 'echo "This is build02"'
          }
        }

      }
    }

  }
}