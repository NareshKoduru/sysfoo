pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        sh 'mvn -version'
      }
    }

    stage('test') {
      steps {
        sh 'echo "This is test"'
      }
    }

    stage('package') {
      steps {
        sh 'echo "This is package"'
      }
    }

  }
}