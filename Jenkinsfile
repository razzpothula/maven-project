node{
stage('scm checkout'){
github.com/razzpothula/maven-project/new/master
}
stage('compile-package'){
\\get the mvnhome path
def mvnhome = tool name:'maven-5',type:maven
sh"${mvnhome}/bin/mvn package"
}
}
