pipeline{
  agent any
  tools{
    java 'jdk21'
    maven 'Maven.3.9.1'
    gradle 'Gradle.8.10.2'
  }

  stages {

    stage ('Build'){
	steps {
      echo "Build application"
	  }
    }

    stage ('Test'){
	steps {
      echo "Test application"
	  }
    }

    stage ('Deploy'){
	steps {
      echo "Deploy application"
	 }
    }
 
  }

  post {
    success {
      echo "Build success
    } 
	failure {
      echo "Build failed"
    } 
	always {
      echo "Build execution finished"
    }
  }

}
