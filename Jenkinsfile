pipeline{
    agent any
    triggers{
        cron('43 * * * 1-5')
    }
    stages{
        stage('vcs'){
            steps{
                git url: 'https://github.com/AnasAnsar1/Multi-branch-test.git', branch: 'src'
            }
        }
        stage('build'){
            steps{
                echo "This is SRC BRANCH"
            }
        }
    }
}