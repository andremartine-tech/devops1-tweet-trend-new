pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/andremartine-tech/devops1-tweet-trend-new.git'
            }
        }
    }
}