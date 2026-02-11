pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
                 bat 'C:\Users\yella\AppData\Local\Programs\Python\Python313\python.exe 1.py'
            }
        }
        stage('Test') { 
            steps {
            echo "stage-2"
            bat 'C:\Users\yella\AppData\Local\Programs\Python\Python313\python.exe 2.py'

            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
