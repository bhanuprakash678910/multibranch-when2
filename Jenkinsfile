pipeline {
    agent any
    stages {
        stage('git code') {
            when {
                not {
                 branch 'dev'
               }
            }
            steps {
               git branch: 'master', url: 'https://github.com/bhanuprakash678910/mavenproj.git'
            }
        }
    }
}
