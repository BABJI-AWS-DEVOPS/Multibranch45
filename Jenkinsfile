node('master') 
{
    stage('S1-CD') 
    {
        git 'https://github.com/BABJI-AWS-DEVOPS/BATCH45VENUWARFILE.git'
    }
}
node('master') 
{
    stage('S2-CB') 
	{
	  sh 'mvn package'
    }
}
