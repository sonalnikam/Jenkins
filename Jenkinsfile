
node {
   // This is to demo github action	
   stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/sonalnikam/Jenkins'
   
   }
	stage('Mvn Package'){
	   // Build using maven
	        def mh = tool name: 'MAVEN_HOME', type: 'maven'
		sh "${mh}/bin/mvn package"
   }
}
 

