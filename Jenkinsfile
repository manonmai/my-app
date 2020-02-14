node{
stage('SCM Checkout'){
 
git'https://github.com/manonmai/my-app'
}
stage('Compile-Package'){
   def mvnHome = tool name: 'Maven', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
