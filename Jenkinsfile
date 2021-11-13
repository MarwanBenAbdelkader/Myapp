pipeline 
{
          agent any
            stages {
                stage('Pull') {
                     steps{
                        script{
                            checkout([$class: 'GitSCM', branches: [[name: '*/marwan']],
                               userRemoteConfigs: [[
                                   credentialsID: '',
                                   url: 'https://github.com/MarwanBenAbdelkader/Myapp.git']]])
                              }
                           }
                        }
                    }          
}                    
