node{
   
   stage("App Build started"){
      echo 'App build started..'
      git credentialsId: 'GithubID', url: ''
      }
   stage("Terraform init"){
   sh 'terraform init'
   }
   stage("Terraform plan"){
   sh 'terraform plan'
   }
   stage("Terraform apply"){
   sh 'terraform apply'
   }
   stage("Terraform Destroy"){
   }
      
      
 }     