
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
                sh 'dpkg-buildpackage -A -rfakeroot -us -uc'
                sh 'cd ..'
            }
        }
        stage('Moving deb files') {
            steps {
                echo 'Starting command'
            }
        }
    }
}
