pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'echo "Hello World"'
        sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
      }
    }
  }
}