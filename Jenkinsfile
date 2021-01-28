pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
                sh 'echo my name is Aniket and today is $(date)'
                sh 'echo my name is Aniket and my current working directory is $(pwd)'
            }
        }
    }
}