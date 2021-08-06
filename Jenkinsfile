pipeline{
        agent any
        environment{
                DHL = credentials("DOCKERHUB_LOGIN")
        }
        stages{
            stage('Debug'){
                steps{
                        sh "docker login -u ${DHL_USR} -p ${DHL_PSW}"
                }
            }
        }
}
