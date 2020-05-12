
node {
   // This is to demo github action	
   stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/sonalnikam/Jenkins'
   
   }
	stage('Mvn Package'){
	   // Build using maven
	        def mh = tool name: 'MAVEN_HOME', type: 'maven'
		sh 'C:/Users/A637979/Desktop/software/apache-maven-3.6.3/bin/mvn package'
   }
}
 

