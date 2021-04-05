pipeline {
  agent any
  stages {
    stage('Clean Directory') {
      steps { sh 'rm -rf node_modules  ' }
    }

    stage('Npm Install') {
      steps { sh 'npm install' }
    }

    stage('Building Node') {
            steps { sh "echo 'starting Node'" }
            steps { sh "echo 'npm start'" }
            steps { sh "echo 'Node strated Successful'" }
    }


  }
}
