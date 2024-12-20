pipeline {
    agent {
        node {
            label 'maven-slave'
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/gppradhan19/tweet-trend-new.git'
            }
        }
    }
}