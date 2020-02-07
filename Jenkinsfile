pipeline {
    agent any
    environment {
        REPO     = credentials('repo-jcartagena')
    }
    stages {
        stage('Example stage 1') {
            steps {
                echo "My test ${env.REPO}" 
            }
        }
    }
}
