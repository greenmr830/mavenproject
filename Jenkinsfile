pipeline{
  agent any
  stages{
    stage("master branch code")
    {
      steps
      {
        git 'https://github.com/greenmr830/mavenproject.git'
      }
    }
    stage("newb branch")
    {
      steps
      {
        git branch: 'newb', url: 'https://github.com/greenmr830/mavenproject.git'
        
      }
    }
  }
}
