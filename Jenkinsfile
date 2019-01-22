node {

   def registry = 'bala19/docker-test'
   def registryCredential = 'dockerhub'

       stage('Git'){
                git 'https://github.com/balajoji04/docker-test.git'
              }
       stage('Build Image'){
                  steps{
                        script {
                                    app = docker.build("bala19/docker-test")
                               }
                    }
            }  
  }

