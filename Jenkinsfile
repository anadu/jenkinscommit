pipeline {
    agent any
    stages {
        stage("list") {
            steps {
                echo "test"
            }
        }  
        stage("Translate"){
            when {
                changelog ".*Translate.*"
            }
            steps {
                echo "Hello World!"
            }
        }
    }
}
