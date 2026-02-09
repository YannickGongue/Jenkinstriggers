pipeline{
    agent any
    stages{
        stage('Webhook Test update new'){
            steps{
                sh 'echo "Github Webhook Trigger Worked this time"'
            }
        }
	stage('build'){
	  steps{
	       sh 'echo "new change commited"'
	       }
        }

    }
}
