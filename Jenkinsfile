pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat '''
                     dir
                     python JenkinsAndGit.py
                     '''
            }
        }
    }
}
