pipeline{
    agent any
    stages{
        stage('Create CF Template'){
            steps{
                sh "ansible-playbook cf-deploy.yml"
            }
        }
    }
}