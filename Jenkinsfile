pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World this is for testing'
            }
        }
        stage('Example Deploy') {
            when {
                branch 'feature'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
