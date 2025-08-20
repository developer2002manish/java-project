node{
  stage('clone the java project'){
     git 'https://github.com/developer2002manish/java-project.git'
  }
  stage('Build the java project'){
     sh 'mvn package'
  }
  stage('successfull done'){
     echo "congratulation done"
  }
}
