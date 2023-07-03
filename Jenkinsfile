pipeline
{
    agent any
    stages
    {
        stage('Build-master')
        {
            when
            {
                branch 'master'
            }
            steps
            {
                echo "Build-Master-branch"
            }
        }
        stage('Build-dev')
        {
            when
            {
                branch 'dev'
            }
            steps
            {
                echo 'Build-Dev branch'
            }
        }
    }
}