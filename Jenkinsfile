pipeline{
    agent any
    stages{
        stage("name"){
            steps{
                echo "my name is sanjay"
                sh 'date'
            }
        }
        stage("build"){
            steps{
                sh 'cat hello.txt'
            }
        }
    }
}
