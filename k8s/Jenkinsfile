pipeline{
    agent any

    stages{

        stage{
            steps {
                script{
                    dockerapp = docker.build("perciliano/kube-news:${env.BUILD_ID}", '-f ./src/Dockerfile ./')
                }
            }
        }



    }
}