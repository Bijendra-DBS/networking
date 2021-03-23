pipeline {
  agent any
  stages {
    stage('Install') {
      steps { sh 'npm install' }
    }

    stage('Test') {
      parallel {
        stage('Building NG APP') {
            steps { echo 'npm build' }
        }

      }
    }

    stage('Build') {
      steps { echo 'Build Test nothing !!' }
    }
  }
}
