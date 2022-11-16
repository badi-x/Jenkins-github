pipeline {
    agent any
    stages {
        stage('No-op') {
            steps {
                echo "Test ${currentBuild.fullDisplayName}"
                sh 'ls'
            }
        }
        
         stage('Sanity check') {
            steps {
                input "Does the staging environment look ok?"
            }
        }

                 stage('Check uname') {
            steps {
                sh 'uname -a'
            }
        }
    }
}