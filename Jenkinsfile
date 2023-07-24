pipeline {
    agent any
stages {

    
         stage('Build-Step') {
 
             steps {
                     echo 'Build Step Jenkins_pi6_test 23 '
                    script{

                         bash '''
            #!/bin/bash
            echo "testing "> ./test.js
            ls -ltr ./*.js
         '''
                    }
                 
             }
         }


    
     

        stage('Change-Step') {
              steps {
                   echo 'Change Step'
                   
              }
        }
}
   
}
