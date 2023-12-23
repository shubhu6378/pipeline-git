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
}