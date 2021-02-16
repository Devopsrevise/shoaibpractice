pipeline
{
    agent any
    stages{
        stage('Checkout from Github')
        {
            steps
            {
                echo "I am in checkout"
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '26002313-f36e-4cb5-b633-b19fd46b5f2a', url: 'https://github.com/Devopsrevise/shoaibpractice.git']]])
                //checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Devopsrevise/shoaibpractice.git']]])
                //git checkout "https://github.com/Devopsrevise/shoaibpractice.git"
                //checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '0a225d14-b0a0-43db-937f-cd49f4f1cb70', url: 'https://github.com/Devopsrevise/shoaibpractice.git']]])
            }
        }
    }
    
    
}
