pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                                        #!/bin/bash
                                        echo "check 1"
                                        git clone https://github.com/Bhavanaht5/C-project.git
                                        cd /var/lib/jenkins/workspace/job-pipeline1/C-project
                                        make
                                        '''
            }
        }
    }
}
