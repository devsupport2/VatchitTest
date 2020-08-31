pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                dir("Upload") {
                    sh 'cd ~/'
                    sh 'cd ..'
                    sh 'cd ..'
                    sh 'cd ..'
                    sh "pwd"
                    sh 'cd /home/Desktop/Upload'
                    sh 'echo "Hello you!" >> test.txt'
                }
                echo 'Hello world! Disco dandiya added' 
            }
        }
    }
}
