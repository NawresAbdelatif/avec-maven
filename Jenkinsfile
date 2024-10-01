pipeline {
    agent any 
    stages {
        stage('Git') {
            steps {
                git branch: 'master', url: 'https://github.com/mhassini/avec-maven.git'
            }
        }
        stage('Mvn') {
            steps {
                sh "mvn --version"
            }
        }
    }
}
