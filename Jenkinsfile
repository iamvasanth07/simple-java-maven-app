pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'docker build -t my-app .'
      }
    }

    // stage('Run') {
    //   steps {
    //     sh 'docker run my-app'
    //   }
    // }

  }
}