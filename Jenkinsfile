pipeline {
  agent any
  stages {
    stage("SCM") {
      steps {
        git 'https://github.com/1234shaik/Spring_Boot_Project.git'
      }
    }
    stage("Build") {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}
