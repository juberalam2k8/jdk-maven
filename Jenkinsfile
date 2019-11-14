node{
     stage('Checkout'){
       git 'https://github.com/juberalam2k8/jdk-maven.git'
       }
     stage('Compile and Package'){
       tool name: 'Maven', type: 'maven'
       mvn clean
       }


}
