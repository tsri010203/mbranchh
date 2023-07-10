node('master') 
{
    stage('Continuous Download_cardss') 
	{
    git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build_cardss') 
	{
    sh label: '', script: 'mvn package'
	}
}
