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

     stage('Test Stage') {
      steps { sh "echo 'Test Node Sucessful'" }
    }

     stage('Deployment Stage') {
      steps { sh "echo ' Node Depoloyed To Production Sucessful'" }
    }



  }
}
