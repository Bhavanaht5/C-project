pipeline {
    agent any
environment{
    PATH = "/usr/bin:$PATH"
}
    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Bhavanaht5/C-project.git'
            }
        }
        stage('build') {
            steps {
sh "cd /var/lib/jenkins/workspace/pipelinec-usingscm/CProject/CProject/"
                sh "make"
            }
        }
     }
}
