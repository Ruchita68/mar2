pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/Ruchita68/mar2.git"
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
