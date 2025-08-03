pipeline{
agent (label 'slave1'}
stages (
stage('SCM Checkout') {
steps {
echo 'Perform SCM Checkout"
git 'https://github.com/SA-
DevOps-0207/java-webapp-project.git
}
}
stage(Application Build') {
steps (
echo 'Perform Application_Build
sh 'mvn clean package
}
}
stage("Deploy to Target Server') {
steps (
echo 'Perform Deployment
}
