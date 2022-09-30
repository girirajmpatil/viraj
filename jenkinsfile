/* groovylint-disable CompileStatic */
pipeline {
    agent any

    stages {
        stage('find_user') {
            steps {
                sh '''
                    echo "finding the user"
                    whoami
                '''
            }
        }
        stage('find_working_dir') {
            steps {
                sh '''
                    echo "$PWD"
                '''
            }
        }
        stage('find_os') {
            steps {
                sh '''
                    cat /etc/os-release
                '''
            }
        }
    }
}
