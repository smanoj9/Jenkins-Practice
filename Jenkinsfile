pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                script{
                    sh """
                        echo "Hello this is Build"
                    """
                }
            }

        }
        stage("Test"){
            steps{
                script{
                    sh """
                        echo "Hello this is test"
                    """
                }
            }

        }
        stage("Deploy"){
            steps{
                script{
                    sh """
                        echo "Hello this is Deploy"
                    """
                }
            }
        }
    }
}