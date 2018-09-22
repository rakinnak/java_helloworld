pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh "javac java_helloworld/HelloWorld.java"
                
            }
        }
        stage('Test Run') { 
            steps {
                sh "cd java_helloworld; java HelloWorld"
            }
        }

    }
}
