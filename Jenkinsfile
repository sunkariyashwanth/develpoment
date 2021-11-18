pipeline{
    agent any
    stages{
        stage ('version checking')
        {
            steps {
                bat 'java -version'
            }
            
        }
        stage ('build')
        {
            steps {
                bat 'git --version'
                build 'task1'
            }
        }
        
        
        
    }
}
