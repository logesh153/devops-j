pipeline {
        agent any
        stages   {   
            stage('Build') {
                steps {
	            echo "Build"
	              }
                   }
            stage('Test') {
                steps {
                    echo "Test"
                      }
                   }
            stage('Integration-Test') {
                steps {
                    echo "Integration-Test"
                      }
                   }
          }
  post  {
    always  { 
        echo 'Pipe runs fine'
           }
    success {
        echo 'Pipeline runs fine'
           }
    failure {
        echo 'Pipeline is failed"
           }
        }
 }
