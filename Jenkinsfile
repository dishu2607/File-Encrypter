pipeline {
 agent any

 stages {

  stage('Build') {
   steps {
    sh '''
    echo "Building Java project..."
    ls
    cd "Password Protection"
    mkdir -p build
    javac -d build src/*.java
    echo "Build successful"
    '''
   }
  }

 }
}
