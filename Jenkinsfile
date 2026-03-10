pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/Meghana-km-05/internals1.git',
                    branch: 'main'
            }
        }
        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
                sh 'first.py'
            }
        }
    }
}
      
