pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        git branch: 'maven', url: 'https://github.com/SatyashreePattanaik/DOCKER-PRACTICE.git'
        sh 'mvn clean install'
      }
    }
    stage ('shell') {
      steps {
        git branch: 'shell-script', url: 'https://github.com/SatyashreePattanaik/DOCKER-PRACTICE.git'
        sh 'bash shell.sh'
      }
    }
    stage ('python') {
      steps {
        git branch: 'python', url: 'https://github.com/SatyashreePattanaik/DOCKER-PRACTICE.git'
        sh 'python3 python.py'
      }
    }
  }
}
 
        
      
