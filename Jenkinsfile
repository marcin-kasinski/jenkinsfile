//@Library('pipeline-library-demo')_
library 'pipeline-library-demo'

pipeline {
    agent  any 
    stages {
        stage('build') {
            steps {
                sh 'echo "master branch" #mvn --version'
            }
        }
        stage('test') {
            steps {
                sh 'echo "master add test stage" #mvn --version'
                sayHello 'Dave'
                sayHello2 'Dave'
            }
        }


    }
}
