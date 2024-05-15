pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/eman-NEMO/Cloud_Task.git'
            }
        }
        stage('Execute Script') {
            steps {

                // Execute the script
                bat 'CloudTask.bat'
            }
        }
    }
}
