pipeline{
    agent any
    stages{
        stage("Compile")
        {
            steps{
                sh 'javac Main.java'
            }
        }

        stage("Run")
        {
            steps{
                sh 'java Main'

            }
        }
    }


    post{

        always{

            sh 'echo "ALWAYS Success"'
        }

        success{

            sh 'echo "Pipeline success"'
        }

        failure{
            sh 'echo "Pipeline failed"'
        }
    }
}