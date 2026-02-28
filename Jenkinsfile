pipeline{
    agent any
    stages{
        stage("STAGE1"){
            steps{
                echo " this s stage1"
                sh "sleep 5"
            }
        }
        stage('STAGE2'){
            steps{
                sh '''
                ll
                pwd
                echo $USER
            }
        }
    }
}