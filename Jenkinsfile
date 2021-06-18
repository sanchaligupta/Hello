node{
  stage('SCM Checkout'){
    git 'https://github.com/sanchaligupta/Hello'
  }
  stage(Compile-Package){
    sh 'mvn package'
  }
}
