pipeline {
  agent any
  stages {
    stage('MENSAJE') {
      steps {
        echo 'Iniciando compilaciÃ³n'
      }
    }

    stage('CAMBIO DE RAMA') {
      parallel {
        stage('CAMBIO DE RAMA') {
          steps {
            sh 'git switch answer4'
          }
        }

        stage('TEXTO') {
          steps {
            echo 'Cambiando de rama'
          }
        }

      }
    }

    stage('COMPILACIÓN') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}