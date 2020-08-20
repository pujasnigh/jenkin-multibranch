node('master') 
{
    stage('ContinuousDownload_loan') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_loan') 
	{
    sh label: '', script: 'mvn package'
	}
   
}
