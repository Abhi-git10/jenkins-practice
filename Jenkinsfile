pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "hi"'
            }
        }
        stage('test') {
            steps {
                sh '''
                    echo "hello world"
                '''
            }
        }
        stage('deploy') {
            steps {
                echo "Deploy stage (add commands here)"
            }
        }
    }
}
