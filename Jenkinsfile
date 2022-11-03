pipeline {
    agent {
        label 'Uchebnaya2'
    }

    stages {
        stage('Hello') {
            steps {
                #sh "docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -d --name elk sebp/elk"
                sh "docker run -d -P nginx"
            }
        }
    }
}
