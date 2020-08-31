pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                dir("~/Desktop/Upload") {
                    sh 'echo "Hello you!" >> test.txt'
                }
                echo 'Hello world! Disco dandiya added' 
            }
        }
    }
}
