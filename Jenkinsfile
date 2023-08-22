pipeline {
    agent any
stages {

    
         stage('Build-Step') {
 
             steps {
                     echo 'Build Step Jenkins_pi6_test 23 '
                    script{

            sh " echo 'testing '> ./test.js "
            sh "ls -ltr ./*.js"
      
                    }
                 
             }
         }


    
     

        stage('Change-Step') {
              steps {
                  
                   echo 'Change Step'
                  snDevOpsChange()
                   
              }
        }
}
   
}
