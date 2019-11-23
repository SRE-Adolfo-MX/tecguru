pipeline {
  agent any
  stages {
    stage('Instanciando') {
      steps {
        echo 'Iniciando proceso'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'uname -a'
          }
        }

        stage('Build Web') {
          steps {
            sh 'php --version'
          }
        }

      }
    }

  }
}