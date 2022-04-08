pipeline {
  agent any
  stages {
    stage('Initial Configuration') {
      steps {
        echo 'Configuracion inicial'
      }
    }

    stage('Download GIT code') {
      steps {
        echo 'Descarga GitHub'
      }
    }

    stage('Execute ADB Server') {
      steps {
        echo 'Emulador'
      }
    }

    stage('Launch Android Emulador') {
      steps {
        echo 'Emulador'
      }
    }

    stage('Appium Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('SonarQube') {
      steps {
        echo 'Evaluate '
        mail(subject: '[App PEPCEA] Se ha distribuido una nueva versión', body: 'Nueva versióm', from: 'matias.gonzalez@estudiantes.utec.edu.uy', to: 'matias.gonzalez@estudiantes.utec.edu.uy')
      }
    }

  }
}