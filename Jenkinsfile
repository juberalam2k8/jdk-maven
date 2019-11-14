node{
     stage('Checkout'){
       git 'https://github.com/juberalam2k8/jdk-maven'
       }
     stage('Compile and Package'){
       tool name: 'Maven', type: 'maven'
       $MAVEN_HOME/bin/mvn package
       }


}
