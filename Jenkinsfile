node('built-in')

{

stage('ContinuousDownload_node') 
   
	 {
	
    git 'https://github.com/sunildevops77/maven.git'
    
	}

stage('Continuousbuild_node') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}
}

