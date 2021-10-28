pipeline {
    agent any
    stages {
        stage('Git-Checkout') {
			steps {
				echo "aqtj获获得资源获得资源ylk获得资源库 ";
				git branch: 'main', url: 'git@github.com:1462893376/thirddemo.git'
			}
		}
        stage('test') {
            steps {
                echo 'build test'
                bat 'python --version'
                bat 'pip install flask pytest'
                bat 'set PYTHONPATH=src;pytest'
            }
        }
    }
}
