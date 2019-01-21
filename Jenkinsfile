node () {
stage ('SCM'){

git 'https://github.com/jenkins-docs/simple-java-maven-app.git'
}


stage ('build') {

sh 'mvn package'

}


stage ('archive the artifacts')
{
archive 'target/*.jar'
}


}

