pipeline {
    agent any
 
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out PayFlow demo code from GitHub...'
            }
        }
        stage('Build') {
            steps {
                echo 'Simulating build of PayFlow landing page...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running placeholder tests...'
            }
        }
      stage('Deploy') {
    steps {
        echo 'Deploying PayFlow landing page to staging...'
        sh '''
            mkdir -p $WORKSPACE/deploy
            cp index.html $WORKSPACE/deploy/index.html
        '''
        echo 'Deployment complete. Files are in workspace deploy folder.'
    }
}
    }
}
