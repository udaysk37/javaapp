pipeline {
  agent any 
    stages {
      stage ('git checkout') {
        steps{
          git branch: 'main', url: 'https://github.com/udaysk36/javaapp.git'
      }
    } 
    stage ('Unittest') {
      steps{
        sh 'maventest'
      }
    } 
  }
} 
