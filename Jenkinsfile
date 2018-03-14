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
        stage('Deploy') {
            steps {
                  sh "cp /var/lib/jenkins/workspace/web/dist/hello.war /home/vivek/tomcat/webapps"
            }
   }
}
}
