
pipeline {
    agent any 
    stages {
        stage('Building Jicofo') {
            steps {
                echo 'Building jicofo' 
            }
        }
        stage('Creating debPackages') {
            steps {
                echo 'Starting command' 
                sh '/resources/build_deb_package.sh'
            }
        }
        stage('Moving deb files') {
            steps {
                echo 'Starting command'
            }
        }
    }
}
