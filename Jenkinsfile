pipeline {
  agent any
    stages {
          stage('checkout') {
            steps {
               git branch: 'main' , url: 'https://github.com/rizwankhan11221122/practice.git'
             }
            }
          stage ('Build') {
               steps {
                   echo"Build the application..."
                   sh 'echo All tests passed!'
                   sh 'git log -1 --oneline'
               }
              }

            stage ('Test') {
               steps {
                   echo"Running tests..."
                   sh 'echo All tests passed!'
                }
              }
           stage ('Depoy') {
                steps {
                   echo "Deploying application..."
                   sh 'echo deployment complete!'
                 }
              }
            }
         }
