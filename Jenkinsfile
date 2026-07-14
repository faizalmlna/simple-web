pipeline {
    agent any

    stages {

        stage('Deploy') {
            steps {
                sh '''
                cp index.html /var/www/html/index.html
                '''
            }
        }

    }
}
