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
                python3 -m black src/Python/*.py
            }
        }
    }
}
