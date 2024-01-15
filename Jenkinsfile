pipeline {
    agent { label 'master'} 
    stages {
        stage ('Thats one small step for man...') {
            steps{
                println '... one giant leap for mankind, and jenkins'
            }
        }
    }
    post {
        always {
            cleanWs deleteDirs: true, notFailBuild: true
        }
    }
}
