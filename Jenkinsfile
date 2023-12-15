pipeline {
    agent any
    stages {
        stage ('Thats one small step for man...') {
            steps{
                println '... one giant leap for mankind'
            }
        }
    }
    post {
        always {
            cleanWs deleteDirs: true, notFailBuild: true
        }
    }
}
