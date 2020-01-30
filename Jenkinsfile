pipeline {
  agent any
  stages {
    stage('Fase1') {
      agent any
      steps {
        echo 'Esta es la fase 1'
        mail(subject: 'Prueba', body: 'Esta es una prueba', from: 'federicog.gonzalez@telefonica.com', to: 'federicog.gonzalez@telefonica.com')
      }
    }

  }
}