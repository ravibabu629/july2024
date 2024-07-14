node('built-in') 
{
    stage('Continuous Download_car') 
	{
    git 'https://github.com/ravibabu629/mycode.git'
	}
    stage('Continuous Build_car') 
	{
    sh label: '', script: 'mvn package'
	}
}
