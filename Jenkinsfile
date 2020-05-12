
node {
   // This is to demo github action	
   stage('SCM Checkout'){
    // Clone repo
	git: 'https://github.com/sonalnikam/Jenkins'
   
   }
	stage('Mvn Package'){
	   // Build using maven
	   
	   sh 'mvn package'
   }
}
 

