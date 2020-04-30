node {
  stage('SCM checkout'){
  git 'https://github.com/tryraghu/my-app'
  }
  stage('Compile Package'){
  sh 'mvn package'
  }
}
