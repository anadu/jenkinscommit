pipeline {
    agent any
    stages {
        stage("list") {
            steps {
                ls -lrt
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
