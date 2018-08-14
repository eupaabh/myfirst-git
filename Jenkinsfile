pipeline {
  agent any
    stages {
      
      stage ('one') {
        steps {
          echo "my first step"
        }
      }
      
      stage ('2') {
        steps {
          input "shall we continue"
        }
      }
      
      stage ('third'){
        when {
          not {
            branch "master"
          }
        }
        steps {
          echo "validation of 3rd"
          
        }
      }
        
        
   }
}
