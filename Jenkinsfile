pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
    post {
    		always {
    			echo 'This will always run'
    		}
    }
}