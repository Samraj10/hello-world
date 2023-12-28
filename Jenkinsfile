pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Samraj10/hello-world.git'
               
         
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
