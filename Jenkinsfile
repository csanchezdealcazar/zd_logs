pipeline {
    agent any
    options {
            timestamps()
           }
    stages {
        stage('Stage One') {
            steps {
                echo 'One'
                sh 'sudo ./scripts/hello.sh'
            }
        }
        
}
