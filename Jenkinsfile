pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/Nagaraju118/Jenkins_task"
      }
    }
    stage("Run")
    {
      steps
      {
        sh "java Demo.java"
      }
    }
  }
}
