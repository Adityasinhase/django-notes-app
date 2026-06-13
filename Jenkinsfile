@Library('Shared')_
pipeline{
    agent { label 'Agent1'}
    stages{
        stage("Code clone"){
            steps{
                sh "whoami"
            clone("https://github.com/LondheShubham153/django-notes-app.git","main")
            }
        }
        
        
    }
}
