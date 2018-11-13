pipeline {
  agent {
    docker {
      image 'node:alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Install') {
      steps {
        echo 'Install Step'
      }
    }
    stage('Lint') {
      steps {
        echo 'Lint Step'
      }
    }
    stage('UnitTest') {
      steps {
        echo 'UnitTest Step'
      }
    }
    stage('BuildImage') {
      steps {
        echo 'BuildImage Step'
      }
    }
    stage('PushImage') {
      steps {
        echo 'PushImage'
      }
    }
    stage('DeployDev') {
      steps {
        echo 'DeployDev Step'
      }
    }
  }
  environment {
    CI = 'true'
  }
}