node{
   stage('SCM Checkout'){
     git 'https://github.com/ouily1/repo5'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      "${mvnHome}/bin/mvn package"
   }
}


