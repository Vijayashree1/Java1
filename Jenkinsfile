pipeline {
    agent any    
    stages {
        stage ("SCM checkout") {
            steps {
                git 'https://github.com/Vijayashree1/Java1.git'          
            }
        }
        stage ("Build") {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
            
