pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload-Loans')
        {
            steps
            {
                git 'https://github.com/krishnain/mavennew.git'
            }
        }
   stage('build-Loans')
        {
            steps
            {
                sh 'mvn package'
            }
        }
    }
    
    
    
    
    
    
    
    
}
