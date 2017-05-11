pipeline {
    agent { label 'spark' }
    stages {
        stage('Build') {
            steps {
                echo "Building..."
                sh "bash touch_tmp"
                echo "Done."
            }
        }
    }
}

