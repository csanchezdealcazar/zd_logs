pipeline {
    agent any
    options {
            timestamps()
           }
    stages {
        stage('Stage One') {
            steps {
                echo 'One'
                sh 'sudo ./scripts/ttt.sh'
            }
        }
        stage('Stage Two'){
            steps{
                echo 'Two'
                sh 'sudo ./scripts/loop.sh'
            }
             
        }
        stage('Stage Three'){
            steps{
                echo 'Three'
                sh 'sudo ./scripts/loop.sh'
            }
             
        }
        stage('Stage Four'){
            steps{
                echo 'Four'
                sh 'sudo ./scripts/ttt.sh'
            }
             
        }
        stage('Stage Five'){
            steps{
                echo 'Five'
                sh 'sudo ./scripts/loop.sh'
            }
             
        }
    }
}
