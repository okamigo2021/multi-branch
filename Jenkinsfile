pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
                echo 'building the application...'
            }
        }
        stage('DEPLOY') {
            when {
                branch 'main'
            } 
            steps {
                echo 'deploying the application...'
            }
        }    
    }
}
