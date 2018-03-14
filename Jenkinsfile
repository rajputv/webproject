pipeline {
    agent any
    stages {
        stage('Check Ant Version') {
            steps {
                  sh "pwd"
                  sh "ant -version"
            }
	}
        stage('Build') {
            steps {
                  sh "pwd"
                  sh "ant all"
            }
        }
   }
}

