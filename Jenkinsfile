pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                sh '''
                    echo "Output of ls -la:"
                    ls -lrt
                    '''
            }
        }

        stage('Build') {
            steps {
                sh '''
                    echo " Building application... "
                    pwd
                    '''
            }
        }
    }
}
