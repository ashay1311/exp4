pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/ashay1311/exp4.git'
            }
        }

        stage('Deploy') {
            steps {
                script {
                    bat 'copy index.html C:\\xampp\\htdocs\\index.html'
                    bat 'copy index1.html C:\\xampp\\htdocs\\index1.html'
                    bat 'copy index2.html C:\\xampp\\htdocs\\index2.html'
                }
            }
        }
    }
}
