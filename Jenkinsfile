pipeline {
  agent any
  stages {
    stage('Checkout Application Files') {
      steps {
        git(url: 'https://github.com/FatimaGalindo/jenkin-test', branch: 'main')
      }
    }

    stage('Checkout Templates Files') {
      steps {
        git(url: 'https://github.com/FatimaGalindo/jenkins-scripts', branch: 'master')
      }
    }

  }
}