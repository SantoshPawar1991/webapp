pipeline{
  agent any
  stages{
    stage('compile_stage'){
      steps{
        sh 'mvn clean compile'
    }
   }
    stage('testing_stage'){
      steps{
        sh 'mvn test'
    }
  }
    stage('install_stage'){
      steps{
        sh 'mvn install'
    }
  }
    stage('Echo Branch'){
      steps{
        echo 'This is master branch'
    }
  }
}
