pipeline {
    agent any

    stages {
        stage('Deploy to Nginx') {
            steps {
                echo 'Memulai proses deploy file...'
                // Menyalin file index.html yang baru di-download dari GitHub ke folder web server
                sh 'cp index.html style.css /var/www/html/'
                echo 'Deploy selesai dengan sukses!'
            }
        }
    }
}
