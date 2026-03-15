pipeline {
    agent any

    stages {

        stage('Checkout Code') {
    steps {
        git branch: 'main', url: 'https://github.com/Vivek-Binod/jenkins-docker-ci-cd'
    }
}

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t 2023bcs0043vivekbinod_2023bcs0043 .'
            }
        }

        stage('Push Image') {
            steps {
                sh 'docker push 2023bcs0043vivekbinod_2023bcs0043'
            }
        }

    }
}
