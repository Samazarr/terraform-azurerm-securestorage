pipeline {
  agent any

  stages {
    stage('test_connexion_github') {
      steps {
        git branch: 'main',
            url: 'https://github.com/Samazarr/terraform-azurerm-securestorage.git'

        sh '''
          ls
          cat test_synch
        '''
      }
    }
  }
}
