pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh '''
        ls
        echo "Hola"
        pwd
        ls -lrt
        uname
        hostname
        touch 1
        '''
      }
    }
    stage('Test'){
      steps{
        echo "Hola mundo 2"
      }
    }
    stage('Deploy'){
      steps{
        echo "Hola mundo 3"
      }
    }
  }
}
