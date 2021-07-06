pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(propagate: true, wait: true, job: 'build')
      }
    }

  }
}