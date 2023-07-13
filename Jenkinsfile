pipeline
{
    agent any
    stages
    {
        stage('prod-branch')
        {
            when
            {
                branch 'prod'
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
