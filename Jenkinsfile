#!/home/rchittala/Downloads/groovy-2.5.8/bin/groovy 
//Declarative Pipeline

pipeline {
    agent any
    stages {
       stage('Build') {
            steps {
                  echo "Hello From BUILD"
            }
       } 
       stage('Test') {
            steps {
                  echo "Hello from test"
            }
       }
       stage('Deploy') {
            steps {
                echo 'Hello from deploy'
            }
       
       }

   } 
}
