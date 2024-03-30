pipeline {
    agent {
        node {
            label'maven'
        }
    }
    stages {
        stage ('Clone-code') {
            steps {
                gitbranch: 'main', url:'https://github.com/banda-mahesh/tweet-trend-new.git'
            }
        }
    }
}