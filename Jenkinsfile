pipeline {
    agent any
    
    tools {
        jdk "jdk17-0-5"
    }
    
    stages {
        stage('Build') {
            steps {
                git branch:'main', url:'https://github.com/theace97/demo-retourdevacances'
                sh "chmod +x ./gradlew"
                sh "./gradlew build"
            }
        }
    
        stage('coucou') {
            steps {
                sh "echo \"coucou\""
            }
        }
    }
}
