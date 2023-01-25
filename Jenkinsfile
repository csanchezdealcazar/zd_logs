pipeline {
    agent any
    options {
            timestamps()
           }
    stages {
        stage('Stage One') {
            steps {
                echo 'One'
                sh './ttt.sh'
            }
        }
        stage('Stage Two'){
            steps{
                echo 'Two'
                sh './loop_no_sleep.sh'
            }
             
        }
        stage('Stage Three'){
            steps{
                echo 'Three'
                sh './loop_no_sleep.sh'
            }
             
        }
        stage('Stage Four'){
            steps{
                echo 'Four'
                sh './ttt.sh'
            }
             
        }
        stage('Stage Five'){
            steps{
                echo 'Five'
                sh './loop_no_sleep.sh'
            }
             
        }
    }
}
