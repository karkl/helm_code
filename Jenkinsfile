pipeline {
    agent any
    environment {
        AZURE_APP_INSIGHT_KEY = credentials('AZURE_APP_INSIGHT_KEY')
        POSTGRES = credentials('POSTGRES_HOST')
    }
    stages {
        stage('Build') {
            steps {
                echo "HELLO KARTHIK"
                echo "POSTGRES_USER is ${POSTGRES_USR}"
                echo "POSTGRES_PSW is ${POSTGRES_PSW}"
                
                
            }
        }
        
    }
}
