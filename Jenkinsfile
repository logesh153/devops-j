pipeline {
        agent { docker { image 'maven:3.6.3' } }
        stages   {   
            stage('Build') {
                steps { 
                    sh 'mvn --version'
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
        echo 'Pipeline is failed'
           }
        }
 }
