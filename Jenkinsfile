node{
   stage('SCM Checkout'){
     git 'https://github.com/Mayaharitha/ansiblePipeline.git'
   }
   stage('Execute playbook'){
    sh 'ansible-playbook -i hosts httpd.yml'
   }
}
