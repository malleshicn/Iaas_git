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
whoami
ssh oss@10.211.203.217
hostname; whoami
'''
          }
        }
      }
    }
  }
}