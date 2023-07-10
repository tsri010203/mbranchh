node('master') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
