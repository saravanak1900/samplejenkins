pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Stage 1 Build"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
        stage('Stage 2 Copy to Nexus') {
            steps {
                echo "Hello Stage 2"
                sh "echo Copying to Nexus"
                sh "hostname"
                sh "uptime"
            }
        }
       stage('Stage 3 Final') {
            steps {
                echo "Stage 3 Final"
                sh "echo Stage 3 Final"
                sh "hostname"
                sh "uptime"
            }
        }


    }
}
