pipeline {
  agent any
  stages {
    stage('Clean Directory') {
      steps { sh 'rm -rf node_modules  ' }
    }

     stage('Install') {
      steps { sh 'npm install' }
    }

    stage('Building Node') {
            steps { sh "echo 'npm start'" }
    }

  }
}
