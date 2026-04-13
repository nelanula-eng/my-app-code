pipeline {
    agent any
    stages {
        stage('Check Tools') {
            steps {
                echo 'Checking if everything is installed...'
                sh 'docker version'
            }
        }
        stage('Finish') {
            steps {
                echo 'GitHub and Jenkins are connected!'
            }
        }
    }
}
