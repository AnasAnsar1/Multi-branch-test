pipeline{
    agent any
    triggers{
        cron('* * * * *')
    }
    stages{
        stage('vcs'){
            steps{
                git url: 'https://github.com/AnasAnsar1/Multi-branch-test.git', branch: 'ver'
            }
        }
        stage('build'){
            steps{
                echo "This is VER BRANCH"
            }
        }
    }
}