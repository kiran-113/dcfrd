node('slavebranch') 
{
    stage('Continuous Download-ls') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build-ls') 
	{
    sh label: '', script: 'mvn package'
	}
}
