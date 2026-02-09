pipeline{
    agent any
    stages{
        stage('Webhook Test update new'){
            steps{
                sh 'echo "Github Webhook Trigger Worked this time"'
            }
        }
	stage('build'){
	  step{
	       sh 'echo "new change commited"'
	       }
        }

    }
}
