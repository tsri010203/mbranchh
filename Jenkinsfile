node('master') 
{
    stage('Continuous Download_cards') 
	{
    git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build_cards') 
	{
    sh label: '', script: 'mvn package'
	}
}
