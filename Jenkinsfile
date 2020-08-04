pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'ckout'
      }
    }

    stage('build ang') {
      parallel {
        stage('build ang') {
          steps {
            echo 'ang'
          }
        }

        stage('bld .net') {
          steps {
            echo 'vzxcv'
          }
        }

      }
    }

    stage('unit test') {
      steps {
        echo 'test'
      }
    }

  }
}