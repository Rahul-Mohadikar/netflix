pipeline{
	agent any
	stages{
		stage('git checkout'){
		steps{
			checkout scm
		}
	}
		stage('build'){
		steps{
			sh '/home/rahul/devops/apache-maven-3.9.6/bin/mvn install'	
}
	}
		stage('deployment'){
		steps{
			sh 'cp target/netflix.war /home/rahul/devops/apache-tomcat-9.0.88/webapps'}}
}

}
