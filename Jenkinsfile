pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi , this is Zulaikha from edureka'
                       }
                               }
                 stage('Two') {
                 steps {
                    input('Do y ou want to proceed?')
                 }
                 }
                 stage('Three') {
                 when {
                       not {
                            branch "master"
                       }
                 }
                 steps {
                       echo "Hellow"
                 }
                 }
               
                }
						  
						   
            }	
