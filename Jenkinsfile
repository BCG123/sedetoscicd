pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
          echo 'Adding a new build step to the build stage'
        }
   }
   stage('Test') {
     steps {
        echo 'Testing...'
        echo 'Adding a new testing step to the Test stage'
        echo 'Adding a new testing step to the Test stage'
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying...'
     }
   }
  }
}
