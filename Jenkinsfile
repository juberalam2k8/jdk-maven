node{
     stage('Checkout'){
       git 'https://github.com/juberalam2k8/jdk-maven'
       }
     stage('Compile and Package'){
       def JAVA_HOME = tool name: 'jdk-11.0.4', type: 'jdk'
       def mvnHome = tool name: 'Maven', type: 'maven'
       bat "${mvnHome}/bin/mvn clean package"
       
       }


}
