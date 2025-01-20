pipeline{
  agent any
  tools{
    java ''
    maven ''
    gradle ''
  }

  stages {

    stage {
      echo "Build application"
    }

    stage {
      echo "Test application"
    }

    stage {
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
