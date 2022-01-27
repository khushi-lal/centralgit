pipeline {
    agent any 
    stages {
    stage('git clone'){
        steps {
            git branch: 'main', url: 'https://github.com/khushi-lal/centralgit.git'
        }
    }
        stage('test'){
        steps{
            echo"testing completed" 
        }
        }
        stage('build'){
        steps{
            echo "build completed"
        }
          
        }
}
}
