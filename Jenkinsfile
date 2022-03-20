pipeline {
    agent any
    stages {
        stage('Main Branch Deploy Code') {
            when {
                branch 'main'
            }
            steps {
                sh """
                echo "Building Artifact from Main branch testing"
                """
 
                sh """
                echo "Deploying Code from Main branch testing"
                """
            }
        }
        stage('Develop Branch Deploy Code') {
            when {
                branch 'develop'
            }
            steps {
                sh """
                echo "Building Artifact from Develop branch testing"
                """
                sh """
                echo "Deploying Code from Develop branch testing"
                """
           }
        }
    }
}
