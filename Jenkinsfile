pipeline {
  agent any
  stages {
    stage('Download Code') {
      steps {
        echo 'Downloading the Code'
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}'
        bat  'cd openmrs'
        bat  'mvn -f pom.xml clean'   
      }
    } 
  }
}
