pipeline {
    agent any
    options{
        timestamps()
    }
    stages {
        stage('Hello') {
            steps {
                sh "sudo ./scripts/hello.sh"
            }
        }
    }
}

