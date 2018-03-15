pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('master') {
      parallel {
        stage('master') {
          steps {
            sh '''

'''
            echo 'stage1 '
          }
        }
        stage('stage2') {
          steps {
            sh '''#!/bin/bash

cd /home/oss/vmware
terraform init
'''
          }
        }
      }
    }
  }
}