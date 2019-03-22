pipeline {
  agent {
    label 'Linux'
  }
  stages {
    stage ('Script') {
      steps {
        sh 'chmod +x roudoudou.sh'
        sh './roudoudou.sh'
      }
    }
  }
}
