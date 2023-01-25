pipeline {
    agent any
    options {
            timestamps()
           }
    stages {
        stage('Stage One') {
            steps {
                echo 'One'
                sh './scripts/ttt.sh'
            }
        }
        stage('Stage Two'){
            steps{
                echo 'Two'
                sh './scripts/loop.sh'
            }
             
        }
        stage('Stage Three'){
            steps{
                echo 'Three'
                sh './scripts/loop.sh'
            }
             
        }
        stage('Stage Four'){
            steps{
                echo 'Four'
                sh './scripts/ttt.sh'
            }
             
        }
        stage('Stage Five'){
            steps{
                echo 'Five'
                sh './scripts/loop.sh'
            }
             
        }
    }
}
