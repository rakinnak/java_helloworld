pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh "pwd"
                sh "javac HelloWorld.java"
                
            }
        }
        stage('Test Run') { 
            steps {
                sh "pwd"
                sh "java HelloWorld"
            }
        }

    }
}
