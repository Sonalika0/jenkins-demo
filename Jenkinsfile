pipeline {
    agent { label 'ubuntu' }
    stages {
        stage('Hello from GitHub') {
            steps {
                echo 'This Jenkinsfile came from GitHub, not typed inside Jenkins!'
                sh 'pwd'
                sh 'whoami'
            }
        }
    }
    post {
        success {
            echo 'GitHub-based pipeline succeeded!'
        }
    }
}
