node('master') 
{
    stage('S1-CD-Payment') 
    {
        git 'https://github.com/BABJI-AWS-DEVOPS/BATCH45VENUWARFILE.git'
    }
}
node('master') 
{
    stage('S2-CB-Payment') 
	{
	  sh 'mvn package'
    }
}
