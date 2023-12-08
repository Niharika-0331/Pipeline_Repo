pipeline {
    agent any
    stages {
        stage('Debug') {
            steps {
                script {
                    echo "Loading Pipeline_Repo library..."
                    def myLibrary = library('Pipeline_Repo')
                    echo "Library contents: ${myLibrary}"
                }
            }
        }
        // Add the rest of your stages here
    }
}

