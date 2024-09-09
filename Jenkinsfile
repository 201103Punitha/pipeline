
pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                 git branch: 'main', url:"https://github.com/201103Punitha/pipeline.git"
            }
        }
        stage('type msg') {  // Missing closing quote fixed
            steps {
                echo "hello this is from pipeline"
            }
        }
    }
}
