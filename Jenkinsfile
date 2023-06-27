pipeline {
    agent any
    stages {
        stage("list") {
            steps {
                echo "test"
            }
        }  
        stage("Test") {
            when {
                changelog ".*Test.*"
            }
            steps {
                echo "Hello World!"
            }
        }
    }
}
