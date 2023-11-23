pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'i want to application developmentplan my '
      }
    }

    stage('code ') {
      steps {
        echo 'development team perform the app development'
      }
    }

    stage('build') {
      steps {
        echo 'build the application'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test the application'
          }
        }

        stage('deploy') {
          steps {
            echo 'delpoy the war files'
          }
        }

        stage('realese') {
          steps {
            echo 'move to realese'
          }
        }

        stage('operate') {
          steps {
            echo 'test the application'
          }
        }

      }
    }

  }
}