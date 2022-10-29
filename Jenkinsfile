node('built-in')
{
stage('Continuous Download_master')
{
git 'https://github.com/dhanamjay94/Maven'
}
stage('Continuous Build_master')
{
sh label: '', script: 'mvn package'
}
}
