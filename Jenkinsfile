pipeline{
    agent any
    environment{
        PATH = "/usr/share/maven/bin/=$PATH"
    }
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
        stage("maven test"){
            steps{
                sh "mvn clean package"
            }
        }
    }

}
