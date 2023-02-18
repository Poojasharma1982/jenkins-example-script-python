pipeline{
agent any
  stages{
    stage('python version'){
      steps{
        sh 'python3 --version'
      }
    }
    stage('hello'){
      steps{
      sh 'python3 hello.py'
      }
    }
  }
}
