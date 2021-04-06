pipeline {
    agent any
environment{
    PATH = "/usr/bin:$PATH"
}
    stages {
        /*stage('git clone') {
            steps {
                git 'https://github.com/Bhavanaht5/C-project.git'
            }
        }
        */
        stage('build') {
            steps {
                sh "/home/ec2-user/home/ec2-user/jenkins/home/ec2-user/jenkins/workspace/pipelinec-usingscm"
                sh "make"
            }
        }
     }
}
