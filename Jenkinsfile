pipeline{
    agent any
    stages{
        stage("this is the first stage 2nd part of pipeline"){
            steps{
                echo "this is my world.. Hello world!!"  
            }
            steps{
                git branch: 'main', url: 'https://github.com/mit33/hello-world.git'  
            }
        }   
    }
}
