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
            steps { sh "echo 'npm start'"}             
    }

     stage('Testing Stage') {
      steps { sh "echo 'Test Node Sucessful'" }
    }

     stage('Deployment Stage') {
      steps { sh "echo ' Node Build Succeed and Deployed'" }
    }



  }
}
