node {
  stage('SCM Checkout'){
    git 'https://github.com/Manash2712/my-app'
  }
  stage('Compile and Package'){
    sh 'mvn install'
  }
}
