pipeline {
    agent any
    tools{
        maven 'MAVEN_HOME'
    }

    stages {
        stage('clone') {
            steps {
                git 'https://github.com/MANIKANTAPT/abhi'
            }
        }
        stage('Build') {
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
