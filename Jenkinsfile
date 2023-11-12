pipeline {
    agent any
    stages {
        stage('git code') {
            when {
                branch 'dev'
                environment name: 'DEPLOY_TO', value: 'production'
            }
            steps {
               git branch: 'master', url: 'https://github.com/bhanuprakash678910/mavenproj.git'
            }
        }
    }
}
