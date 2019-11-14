node{
     stage('Checkout'){
       git 'https://github.com/juberalam2k8/jdk-maven'
       }
     stage('Compile and Package'){
       def mvnHome = tool name: 'Maven', type: 'maven'
       bat "${mvnHome}/bin/mvn clean package"
       
       }


}
