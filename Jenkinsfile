node('slavebranch') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/kiran-113/dcfrd.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}