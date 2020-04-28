pipeline {
  agent {
    docker {
      image 'registry.cn-hangzhou.aliyuncs.com/guobinbin/automation:interfacetest'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('test') {
      steps {
        sh '''pwd
ls'''
      }
    }

  }
}