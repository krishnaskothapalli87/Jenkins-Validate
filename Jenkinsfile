pipeline{
  agent any
  tools{
    java ''
    maven ''
    gradle ''
  }

  stages {

    stage ('Build'){
      echo "Build application"
    }

    stage ('Test'){
      echo "Test application"
    }

    stage ('Deploy'){
      echo "Deploy application"
    }
 
  }

  post{
    always {
      echo "Build completed
    } success {
      echo "Build successful"
    } failed {
      echo "Build failed"
    }
  }

}
