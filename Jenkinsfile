pipeline {
  agent any
  stages {
    stage('Clean Directory') {
      steps { echo 'rm -rf node_modules ' }
    }

     stage('Install') {
      steps { echo 'npm install' }
    }

    stage('Building NG APP') {
            steps { echo 'npm build' }
    }

  }
}
