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
          sh "touch /tmp/deepu.txt"
               }
            }
    }
  }
}
