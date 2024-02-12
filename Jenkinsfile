pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'whoami'
                sh 'chmod +x /home/parallels/.sdkman/candidates/maven/current/bin/mvn'
                sh '/home/parallels/.sdkman/candidates/maven/current/bin/mvn -B -DskipTests clean package' 
            }
        }
    }
}
