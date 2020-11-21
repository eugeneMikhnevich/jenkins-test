pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    bat 'FOR /L %%G IN (1,1,30000) DO echo %%G'
                }
                timeout(time: 1, unit: 'MINUTES') {
                    bat 'FOR /L %%G IN (1,1,30000) DO echo %%G'
                }
            }
        }
    }
}
