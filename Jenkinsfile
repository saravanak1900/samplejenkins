pipeline {
    agent { any }
    stages {
        stage('build') {
            steps {
                echo "Hello UK!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
