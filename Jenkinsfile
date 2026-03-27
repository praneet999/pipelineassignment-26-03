pipeline {
   agent any
   stages {
       stage('Checkout Code') {
           steps {
               echo 'Pulling code from repository'
           }
       }
       stage('Build') {
           steps {
               echo 'Compiling the application'
           }
       }
       stage('Test') {
           steps {
               echo 'Running test cases'
           }
       }
       stage('Package') {
           steps {
               echo 'Packaging the application'
           }
       }
       stage('Deploy') {
           steps {
               echo 'Deploying to server'
           }
       }
   }
}
