pipeline {
  agent {
    docker {
      image 'registry.cn-hangzhou.aliyuncs.com/guobinbin/automation:interfacetest'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh '''pwd
ls'''
          }
        }

        stage('test2') {
          steps {
            sleep 5
            sh 'pwd'
          }
        }

        stage('test4') {
          steps {
            sh 'pwd'
          }
        }

      }
    }

  }
}