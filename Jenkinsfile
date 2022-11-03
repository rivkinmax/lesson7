pipeline {
    agent {
        label 'Uchebnaya2'
    }

    stages {
        stage('Hello') {
            steps {
                sh "docker run -d -P nginx"
            }
        }
    }
}
