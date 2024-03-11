pipeline {
  agent any
  stages {
    stage('pull from github') {
      steps {
        sh 'ssh hongjin@10.8.18.12 "cd /home/hongjin/Music/Jenkins/blue_ocean && ./first_pull.sh"'
      }
    }

  }
}