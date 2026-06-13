@Library('Shared')_
pipeline{
    agent { label 'Agent1'}
    stages{
        stage("Code clone"){
            steps{
                sh "whoami"
                clone("https://github.com/Adityasinhase/django-notes-app.git","main")
            }
        }
        
        
    }
}
