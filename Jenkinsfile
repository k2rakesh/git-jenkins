node{
  stage('SCM Checkout'){
    git 'https://github.com/k2rakesh/git-jenkins'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mnv package'
        }
}
