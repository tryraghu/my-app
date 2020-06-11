node {
   stage('SCM Checkout'){
      git 'https://github.com/tryraghu/my-app.git'
    }
    stage('Compile-Package'){
       dif mvnHome = tool name: 'maven-3', type: 'maven'
    sh 'mvn package'
    }
    
}
