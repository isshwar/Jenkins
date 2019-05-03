pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                echo  "Initializing the Code File"
                sh 'cd java-maven-junit-helloworld-master'
            }
        }
 
        stage ('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
 
         stage ('Deploy') {
            steps {
                echo 'Deployed an Artifact'
            }
        }
    }
}
