pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'git@github.com:mekhamata/helloworldpython.git', branch: 'master', credentialsId: 'github-ssh', poll: true)
      }
    }

    stage('Build') {
      steps {
        echo 'hello from build'
      }
    }

    stage('Test') {
      steps {
        echo 'hello from test'
      }
    }

    stage('Package') {
      steps {
        echo 'hello from package'
      }
    }

  }
}