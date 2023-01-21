node('built-in') 
{
    stage('Continuous Downlod_master') 
	{
    git 'https://github.com/clemenrance/multiple_pipeline_repository.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
