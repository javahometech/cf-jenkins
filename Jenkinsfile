pipeline{
    agent any
    stages{
        stage('Create CF Template'){
            steps{
                sh "ansible-playbook -vvv cf-deploy.yml"
            }
        }
    }
}
