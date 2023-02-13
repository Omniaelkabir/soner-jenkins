pipeline {
  agent any
  stages {
    stage('Scan') {
      steps {
        withSonarQubeEnv(installationName: 'mysq') { 
		sh '''
                echo "Hello, World!"
                '''
        }
      }
    }
  }
}
