pipeline {
 agent any
    tools {
     maven 'mymaven'
   }
 stages {
    stage ('code checkout'){
       steps {
        git 'https://github.com/prashanth-1993/game-of-life.git'
       }
    }
  stage ('code compile') {
   steps {
     sh 'mvn compile'
    }
  }
 }
}