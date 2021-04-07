pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                                        #!/bin/bash
                                        echo "check 1"
                                      
                                        cd /var/lib/jenkins/workspace/job-pipeline1/C-project/CProject/Build_CProject
                                        make
                                        '''
            }
        }
    }
}
