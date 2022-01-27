pipeline {
  agent any
  stages {
    stage('MENSAJE') {
      steps {
        echo 'Iniciando compilaci√≥n'
      }
    }

    stage('CAMBIO DE RAMA') {
      parallel {
        stage('CAMBIO DE RAMA') {
          steps {
            sh 'git checkout answer4'
          }
        }

        stage('TEXTO') {
          steps {
            echo 'Cambiando de rama'
          }
        }

      }
    }

    stage('COMPILACI”N') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}