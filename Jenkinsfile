pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/pavansw/simpleMavenJunit.git', branch: 'master', poll: true)
      }
    }

  }
}