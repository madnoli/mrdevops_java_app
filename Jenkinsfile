/* groovylint-disable-next-line CompileStatic */
pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                script {
                    git branch: 'mian', url: 'https://github.com/madnoli/mrdevops_java_app.git'
                }
            }
        }
    }
}
