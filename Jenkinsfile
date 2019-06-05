pipeline {
  agent any
  stages {
    stage('Download Code') {
      steps {
        echo 'Downloading the Code'
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        bat  ' git clone https://github.com/sudheer51/TQAug18.git'
        bat  'mvn -f openmrs/pom.xml clean'
        
      }
    }
    
  }
}
