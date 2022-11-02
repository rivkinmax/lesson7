pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh "Docker run -d -P nginx"
            }
        }
    }
}
