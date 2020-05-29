node{
  stage('SCM Checkout'){
       git 'https://github.com/k-vishal/restj.git'
       }
  stage('Mvn Package'){
      def mvn = tool (name: 'Maven', type: 'maven') + '/bin/mvn'
      sh "${mvn} Package"
      }
}
