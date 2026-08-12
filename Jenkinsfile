pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        success{
            echo 'pipeline executed  successfully!
        }
        failure{
            echo 'pipeline failed. please check the logs for details.'
        }
    }
}
