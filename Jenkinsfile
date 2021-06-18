node{
  stage('SCM Checkout'){
    git 'https://github.com/sanchaligupta/Hello'
  }
  stage('Compile-Package'){
    // Get maven home path 
    def mvnHome = tool name: '', type: 'maven'
    sh "${mvn package}/bin/mvn package"
  }
}
