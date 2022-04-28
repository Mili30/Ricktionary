pipeline {
  agent any
  stages {
    stage('Testing'){
      steps {
        echo 'running test'
        sh 'mvn test'
      }
    }
    stage('Build'){
      steps{
        echo 'Building jar files...'
        sh 'mvn package'
      }
    }
  }
}
