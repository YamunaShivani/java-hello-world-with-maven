node{
    
    stage('SCM checkout')
    { 
    
    git 'https://github.com/YamunaShivani/java-hello-world-with-maven'
    
}
stage('compile pkg'){
	def mvnHome = tool name: 'maven-3', type: 'maven'
	sh "${mvnHome}/bin/mvn package"
    
    
}

}
