node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/clemenrance/multiple_pipeline_repository.git'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
