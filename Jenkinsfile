pipeline {
    agent none

    stages {
        stage('Run script') {
            agent { label 'test' }
            steps {
                 bat "C:\Users\Tzvi\AppData\Local\Microsoft\WindowsApps\python.exe tzvi_checkup.py
            }
        }
    }
}
