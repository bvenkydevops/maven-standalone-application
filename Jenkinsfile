pipeline{
  agent any
  stages{
    stage("download"){
      steps{
        echo  'hello'
    }
  }
    stage("build"){
      steps{
        sh 'mvn clean package'
      }
    }
}
}
