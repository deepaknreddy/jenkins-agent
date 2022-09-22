#!groovy
pipeline
{
  agent { label 'agent-1' }
  stages 
  {
    stage(" to create file")
    {
      steps {
        script {
          sh "echo 'iam deepak\'s jenkins agent'>/tmp/deepu.txt"
               }
            }
    }
  }
}
