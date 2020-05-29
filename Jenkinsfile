node{
  stage('SCM Checkout'){
       git 'https://github.com/k-vishal/restj.git'
       }
  stage('Compile Package'){
      def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn'
      sh 'mvn Package'
      }
}
