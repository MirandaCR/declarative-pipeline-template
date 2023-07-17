pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        echo "Run Build"
        sh 'chmod a+x run_build_script.sh'
        sh './run_build_script.sh'
      }
    }
    stage('Test'){
      steps{
        echo "Run Test"
      }
    }
  }
}
