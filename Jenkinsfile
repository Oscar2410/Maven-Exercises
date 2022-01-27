pipeline {
  agent any
  stages {
    stage('MENSAJE') {
      steps {
        echo 'Iniciando compilación'
        sh 'mvn clean install '
        echo 'Compilación finalizada'
      }
    }

  }
}