node{
  stage('SCM Checkout'){
    git 'https://github.com/sanjeet1992/hello-world'
  }
  stage('Compile-Package'){
  //get maven home path
    def mvnHOME = tool name: 'maven-3', type: 'maven'
    sh "${mvnHOME}/bin/mvn package
  }
}
