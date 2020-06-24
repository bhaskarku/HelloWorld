pipeline{
    agent any
    stages {
        stage('build'){
            steps{
                echo 'Hello World..!'
                 echo "Build Id: ${env.BUILD_ID}, Build Url: ${env.BUILD_URL}"
            }
        }
        stage('test'){
            steps{
                echo 'testing..!'
            }
        }
        stage('deploy'){
            steps{
                echo 'Deploying..!'
            }
        }
    }
}
