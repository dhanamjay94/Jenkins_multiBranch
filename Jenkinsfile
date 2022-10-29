node('master') 
{
stage('Continuous Download') 
{
git 'https://github.com/dhanamjay94/Maven'
}
stage('Continuous Build') 
{
sh label: '', script: 'mvn package'
}
}
