node{
   stage ('SCM Checkout')
   {
    git https://github.com/vrbksdet/FirstSeleniumMaven.git
   }
   stage ('maven')
   {
      def mvnHome = tool name: 'Maven-3.8.4', type: 'maven'
      sh "{mvnHome}/bin/mvn test"
   
   }
}
