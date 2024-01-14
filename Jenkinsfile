pipeline{
    agent any
    stages{
        stage("this is the first stage of pipeline"){
            steps{
                echo "this is my world.. Hello world!!"
            } 
        }
        stage("git checkot"){
            steps{
                git branch: 'main', url: 'https://github.com/mit33/hello-world.git'
            } 
        }
        stage("maven work"){
            steps{
                sh "mvn --version"
            }
    }

}
