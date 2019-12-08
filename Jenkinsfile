pipeline {
    agent any


    stages 
    {  
        
        stage ('SCM Checkout') {
          git 'https://github.com/pranjalsurve/maven-project/maven-project'
         }
    
    }
    {
                            
        
        stage ('Testing Stage') {


            steps {
                withMaven(maven : 'mavan')
                {
                    sh 'mvn test'
                }
                  }
                                 
        }
		}
		}
		
