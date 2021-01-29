pipeline {
    agent any


    stages {
        stage('Pull Code') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/chaitu-padi/JenkinTester.git'
		echo "git setup is done------"
            }
		}	
        stage('Run Code') {
            steps {
                bat "dir"
                bat "javac HelloWorld.java"
                bat "java HelloWorld"

            }          
        }
    }
}
