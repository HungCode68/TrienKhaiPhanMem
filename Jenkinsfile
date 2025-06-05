pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/HungCode68/TrienKhaiPhanMem.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Đang build project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Đang chạy test...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy xong!'
            }
        }
    }
}
