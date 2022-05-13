pipeline {
    agent any

    stages {
        stage('stage1') {
            steps {
                bat '''
                     dir
                     python JenkinsAndGit.py
                     '''
            }
        }
    }
}
