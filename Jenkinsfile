pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t 2023bcs0043vivekbinod/2023bcs0043_2023bcs0043 .'
            }
        }

        stage('Push Image') {
            steps {
                sh 'docker push 2023bcs0043vivekbinod/2023bcs0043_2023bcs0043'
            }
        }

    }
}
