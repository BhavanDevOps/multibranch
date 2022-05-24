## Simple pipeline
pipeline { 
  
   agent any

   stages {
   
     stage('Checkout the data') { 
        steps { 
           echo "Checkout the data" 
        }
     }
     
     stage('create data') { 
        steps { 
           mkdir /tmp/appdata
        }
      }

         stage("deploy apps files") { 
         steps { 
           cp -r . /tmp/appdata
         }

     }
  
   	}

   }
