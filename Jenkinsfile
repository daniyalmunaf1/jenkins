pipeline {
    agent none

    stages {
        stage('Build on World') {
            agent {
                label 'myslave' // Replace 'slave-node' with the actual label assigned to your slave node
            }
            steps {
                // Perform build steps on the slave node
                sh 'echo "Building on slave node..."'
            }
        }
        // Other stages
    }
}
