node('slavebranch') 
{
    stage('Continuous Download-sales') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build-sales') 
	{
    sh label: '', script: 'mvn package'
	}
}
