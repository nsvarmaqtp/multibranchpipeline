node('master') 
{
    stage('ContinuousDownload -loans') 
    {
      git 'https://github.com/selenium-saikrishna/maven.git'
    }
    
    stage('ContinuousBuild -loans')
    {
        sh label: '', script: 'mvn package'
    }
  
    
    
    
    
}
