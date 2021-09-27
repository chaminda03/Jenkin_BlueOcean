pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building '
          }
        }

        stage('Paralal build') {
          steps {
            echo 'parallel build'
          }
        }

      }
    }

    stage('testing') {
      steps {
        echo 'testing'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy stage'
      }
    }

  }
}