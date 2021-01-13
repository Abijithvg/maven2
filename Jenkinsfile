node{
stage('SCM Checkout')
{
git 'https://github.com/Abijithvg/maven2.git'
}
stage('compile')
{
 def Home=tool name: 'maven-1', type: 'maven'
sh "${Home}/bin/mvn package"
}
}
