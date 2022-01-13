
pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                    sh 'curl -fsSL https://raw.githubusercontent.com/ZupIT/horusec/main/deployments/scripts/install.sh | bash -s latest'          
                  }
        }
    }
}
