pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mymavennode"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
