pipeline {
    agent none

    stages {
        stage('Build on Slave') {
            agent {
                label 'firstnode' // Replace 'slave-node' with the actual label assigned to your slave node
            }
            steps {
                // Perform build steps on the slave node
                sh 'echo "Building on slave node..."'
            }
        }
	stage('Test') {
            steps {
                // Perform test steps here
                sh 'echo "Testing..."'
            }
        }
        stage('Deploy') {
            steps {
                // Perform deployment steps here
                sh 'echo "Deploying..."'
            }
        }
        // Other stages
    }
}

