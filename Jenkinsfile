def arch = 'amd64';
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                if ($arch == 'i386') {
                    echo 'Supported Architecture'
                } else {
                    echo 'Unsupported Architecture'
                }
            }
        }
    }


}
