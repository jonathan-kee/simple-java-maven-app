pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh '/home/parallels/.sdkman/candidates/maven/current/bin/mvn -B -DskipTests clean package' 
            }
        }
    }
}
