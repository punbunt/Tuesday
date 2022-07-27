pipeline {
  agent any
  stages {
    stage('Starting...') {
      steps {
        echo 'Starting' 
      }
    }
    stage('Compiling') { //บอกว่าทำงานยังไง ขึ้นอยู่กับระบบปฏิบัติการ
      steps {
        sh  'javac Start.java'    //Unix and Mac Command
      }
    }  
    stage('Testing') {
      steps {
        sh 'java Start.java'  
      }
    }
  }
  
}
