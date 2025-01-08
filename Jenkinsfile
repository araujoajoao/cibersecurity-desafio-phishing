pipeline {
    agent any

    stages {
        stage('Environment Setup') {
            steps {
                echo 'Setting up Kali Linux environment...'
                // Example command for environment configuration
                sh '''
                # Ensure the environment is updated
                sudo apt-get update -y
                sudo apt-get upgrade -y
                
                # Install setoolkit
                sudo apt-get install -y setoolkit
                '''
            }
        }

        stage('Verify Tools Installation') {
            steps {
                echo 'Verifying setoolkit installation...'
                // Check if setoolkit is installed
                sh 'which setoolkit || echo "setoolkit not found!"'
            }
        }

        stage('Configure Phishing Attack (Educational Purpose)') {
            steps {
                echo 'Configuring phishing environment for Instagram (study only)...'
                sh '''
                # Running commands to set up phishing
                sudo su -c "
                echo 'Launching Social-Engineering Toolkit...'
                echo -e '1\n2\n3\n2\n' | setoolkit
                "
                '''
            }
        }

        stage('Fetch Machine IP') {
            steps {
                echo 'Retrieving machine IP for phishing setup...'
                sh 'ifconfig | grep inet | head -n 1'
            }
        }

        stage('Clone Instagram Site') {
            steps {
                echo 'Cloning Instagram site for credential harvesting setup (study purpose only)...'
                sh '''
                # Simulate the cloning of the Instagram site
                echo 'Cloning http://www.instagram.com for educational purposes...'
                '''
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution complete. Ensure the project is used responsibly and ethically.'
        }
        success {
            echo 'Phishing environment successfully configured (educational purpose only).'
        }
        failure {
            echo 'Pipeline failed. Check logs and configurations.'
        }
    }
}
