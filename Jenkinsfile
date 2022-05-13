pipeline {
    agent any

    stages {
        stage('newstage1') {
            steps {
                bat '''
                     dir
                     python JenkinsAndGit.py
                     '''
            }
        }
    }
}
