pipeline{
    agent any
    stages{
        stage('vcs'){
            steps{
                git url: 'https://github.com/AnasAnsar1/Multi-branch-test.git', branch: 'les'
            }
        }
        stage('build'){
            steps{
                echo "This is LES BRANCH"
            }
        }
    }
}