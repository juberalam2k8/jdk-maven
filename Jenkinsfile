node{
     stage('Checkout'){
       git 'https://github.com/juberalam2k8/jdk-maven'
       }
     stage('Compile and Package'){
       def mvnHome = tool name: 'Maven', type: 'maven'
       tool name: 'JAVA_HOME', type: 'jdk'
       echo %JAVA_HOME%
       bat "${mvnHome}/bin/mvn clean package"
       
       }


}
