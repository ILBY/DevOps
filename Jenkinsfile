pipeline {
    agent any

    stages {
        stage('Name_job') {
            steps {
                sh 'echo ${JOB_NAME}'
            }
        }
        stage('Build_ID') {
            steps {
                sh 'echo ${BUILD_ID}'
            }
        }
    }
}
