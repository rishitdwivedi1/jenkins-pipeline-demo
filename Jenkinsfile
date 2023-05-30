pipeline {
    agent any

    stages {
        stage("First_Stage__Job")
        {
        parallel{
            
        
        stage('First_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
         stage('Second_Job_') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
                    stage('Third_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
      
        stage('Fourth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
        stage('Fifth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
        stage('Sixth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
        stage('Seventh_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
        stage('Eighth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        } 
        stage('Nineth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
        stage('Tenth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
               stage('Eleventh_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
                   stage('Twelveth_Job') {
            steps {
         
          sh 'echo "4*a(1)" | bc -l' 
                  
                   }
        }
        
        
        }
    }
}
    post {
    always {
      // Your post-build actions here

      // Send notification to Slack
      slackSend(channel: '#jenkins_test', message: 'Build Triggered!')
    }
        success {
                  slackSend(channel: '#jenkins_test', message: 'Build Executed Successfully!')

        }
          failure {
                  slackSend(channel: '#jenkins_test', message: 'Build Execution Failed!')

        }
  }
}
