pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'whoami'
                sh '/home/parallels/.sdkman/candidates/maven/current/bin/mvn -B -DskipTests clean package' 
            }
        }
    }
}
