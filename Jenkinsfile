pipeline {
  agent any
  stages {
//     stage('Verify browsers are installed') {
//       steps {
//         sh 'mvn --version'
//         sh 'google-chrome --version'
//         sh 'firefox --version'
//       }
//     }
    stage('Run Tests') {
      steps {
        sh './mvnw clean test'
      }
    }
  }
}
