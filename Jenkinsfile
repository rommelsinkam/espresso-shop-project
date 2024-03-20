pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from your version control system
                git'https://github.com/rommelsinkam/espresso-shop-project'
            }
        }
        stage('Build') {
            steps {
                // Build your project (replace this with your actual build commands)
                 echo 'first build'
            }
        }
        stage('Unit Test') {
            steps {
                // Run unit tests (replace this with your actual unit test commands)
                echo 'first test'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy your application (replace this with your actual deployment commands)
              echo 'first deploy'
            }
        }
    }
}
