node('slavenode') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/kiran-113/first.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
