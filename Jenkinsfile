pipeline {
  agent any
  trigger {
    githubPush()
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello '
      }
    }

  }
}
