pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Install Dependencies') {
            steps {
                script {
                    bat 'curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py'
                    bat 'C://Users//anari//AppData//Local//Programs//Python//Python311 get-pip.py'
                    
                    // Use the full path to pip
                    sh 'C://Users//anari//AppData//Local//Programs//Python//Python311 -m pip install -r requirements.txt'
                }
            }
        }
      

    }
}
