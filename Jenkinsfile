pipeline
{
agent any
  stages
  { 
    stage ('git clone')
   {steps
    { sh 'echo downloading code' }
   }
   stage ('compile code')
   {steps
    {sh 'echo compiling code'}
   }
   stage ('code build')
   {steps
    {sh 'echo buding the code'}
   }
   stage ('get approval')
   {input "please approve the deployment?" }
   
   stage('deployment')
   {steps
    {sh 'echo deploying the job' }
      } 
  }
}
   
