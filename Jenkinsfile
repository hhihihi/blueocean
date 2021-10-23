pipeline {
  agent any
  stages {
    stage('Test1') {
      agent any
      steps {
        sh '''#! /bin/bash
echo "Testing...1"'''
      }
    }

    stage('Test2') {
      agent any
      steps {
        sh '''#! /bin/bash
echo "Testing...2"'''
      }
    }

  }
}