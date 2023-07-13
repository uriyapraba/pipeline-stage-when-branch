pipeline
{
    agent any
    stages
    {
        stage('master-branch')
        {
            when
            {
                branch 'master'
            }
            steps
            {
                echo "Deploy from master"
            }
        }
        stage('dev-branch')
        {
            when
            {
                branch 'dev'
            }
            steps
            {
                echo "Deploy from dev"
            }
        }
    }
}