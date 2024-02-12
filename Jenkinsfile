pipeline {
    agent any
    tools {
            // Install the Maven version configured as "M3" and add it to the path.
            maven "M3"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'whoami'
                sh "chmod +x -R ${env.WORKSPACE}"
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
