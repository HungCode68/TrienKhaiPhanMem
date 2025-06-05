pipeline {
    agent any

    stage('Checkout') {
    steps {
        git branch: 'main', url: 'https://github.com/HungCode68/TrienKhaiPhanMem.git'
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
