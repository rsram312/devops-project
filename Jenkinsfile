node {
    def app

    stage('Checkout code') {
      checkout scm
    }

    stage('Docker pull'){
      app = docker.pull('python')
    }
}
