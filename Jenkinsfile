pipeline{

agent { node { label 'workstation' }}


stages{

  stage('unit test'){
      steps{
       // sh 'python -m unit test'
        echo 'unit test'
      }
  }
  stage('code analysis'){
      steps{
        echo 'code analysis'
      }
  }

  stage('security scans'){
      steps{
        echo 'security scans'
      }
  }

  stage('artifact creation'){
      steps{
        echo 'artifact creation'
      }
  }
}



}