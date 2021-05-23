pipeline {
    agent any

    stages {
        stage('Build from SCM') {
            steps {
                git([url: 'https://github.com/v-kostyukov/Jenkins-samples.git', branch: 'master'])

                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
