pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world SCM!' 
            }
        }
        
        stage('Format')
        {
            steps {
                sh 'python3 -m black .'
                sh 'git add . && git commit -C HEAD --amend'
            }
        }
    }
}
