pipeline {

    agent any

    stages {

        stage('run.sh') {

            steps {

                sh '''
                sh run.sh
                '''

            }

        }
        stage('Post Checks') {

            steps {

                sh '''
                echo "lgtm"
                '''

            }

        }

    }

}