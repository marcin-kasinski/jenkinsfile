pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "master branch" #mvn --version'
            }
        }
        stage('test') {
            steps {
                sh 'echo "master add test stage" #mvn --version'
            }
        }
    }
}
