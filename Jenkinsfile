pipeline {
  agent any
  stages {
    stage('Download Code') {
      steps {
        echo 'Downloading the Code'
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        echo "Jenkins Workspace ${env.WORKSPACE}"
        dir_path =   "${env.WORKSPACE}/openmrs"  
        bat dir_path mvn clean
      }
    } 
  }
}
