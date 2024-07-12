node('built-in') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/ravibabu629/mycode.git'
	}
    stage('Continuous Build') 
	{
   sh label: '', script: 'mvn package'
}
}
