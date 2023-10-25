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
                  
                    bat 'C://Users//anari//AppData//Local//Programs//Python//Python311 get-pip.py'
                    
                    // Use the full path to pip
                    bat 'C://Users//anari//AppData//Local//Programs//Python//Python311 -m pip install -r requirements.txt'
                }
            }
        }
      

    }
}
