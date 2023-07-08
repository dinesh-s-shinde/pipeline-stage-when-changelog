pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changelog ".*some text*."
            }
            steps {
                echo "Hello World changelog"
            }
        }
    }
}