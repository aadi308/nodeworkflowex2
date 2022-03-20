pipeline {
    agent any
    stages {
        stage('Main Branch Deploy Code') {
            when {
                branch 'main'
            }
            steps {
                sh """
                echo "Building Artifact from Main branch tested"
                """
 
                sh """
                echo "Deploying Code from Main branch tested"
                """
            }
        }
        stage('Develop Branch Deploy Code') {
            when {
                branch 'develop'
            }
            steps {
                sh """
                echo "Building Artifact from Develop branch tested"
                """
                sh """
                echo "Deploying Code from Develop branch tested"
                """
           }
        }
    }
}
