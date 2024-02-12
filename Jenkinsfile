pipeline {
    agent any
    tools {
            // Install the Maven version configured as "M3" and add it to the path.
            maven "3.8.5"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'whoami'
                sh '/home/parallels/.sdkman/candidates/maven/current/bin/mvn -B -DskipTests clean package' 
            }
        }
    }
}
