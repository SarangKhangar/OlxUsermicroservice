pipeline {
    agent any

    stages {
        
        stage('Complile') {
            steps {
                bat 'mvn clean compile'
            }
        }
         stage('Run') {
            steps {
                bat 'mvn package'
            }
        }  
          stage('Test report using  jacoco') {
            steps {
                echo 'jacoco'
            }
        }
        stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}
