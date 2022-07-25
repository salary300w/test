pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh '''chmod a+x echo.sh
                      ./echo.sh
                        '''
            }
        }
    }
}