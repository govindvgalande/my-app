node{
   stage ('SCM Checkout')
   {
   git 'https://github.com/govindvgalande/my-app'
   }
   
   stage('Compile-package')
   {
   def mvnHome = tool name : 'maven 3.8.6', type:'maven'
   sh "${mvnHome}/bin/mvn/ package"
   }
   }
