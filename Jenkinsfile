node
{
stage("Cloning from Git")
{
git branch: 'main', url: 'git@github.com:deepak199310/Jenkinspipelines2.git'
}
stage("Run a Shell Script")
{
sh "chmod 755 hello.sh"
sh "./hello.sh"
}
}
