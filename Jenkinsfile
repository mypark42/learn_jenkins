pipeline {
    agent any
    stages {
        stage('build') {
            steps {
		sh 'cc test.c'
		sh './a.out'
            }
        }
    }
}
