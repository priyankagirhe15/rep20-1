node('master') 
{
    stage('Continuous Download_Loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loans1') 
	{
    sh label: '', script: 'mvn package'
	}
   
}
