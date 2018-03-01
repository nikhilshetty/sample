pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "hello world"'
        echo 'hello'
      }
    }
    stage('test') {
      steps {
        build(job: 'lklklk', propagate: true, wait: true)
      }
    }
  }
}