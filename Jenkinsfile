pipeline {
agent any
  stages{
    stage ("git clone"){
      steps{
      git "https://github.com/srinu-dev/vini.git"
      }
    }
    stage ("compile"){
      steps{
      echo "compile the code"
        sh "mvn compile"
      }
    }
    stage("package"){
      steps{
      echo "package the code"
        sh "mvn package"
      }
    }
  }
}
