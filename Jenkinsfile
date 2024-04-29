pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh '/opt/apache-maven-3.5.3/bin/mvn package' 
            }
        }
    }
}

