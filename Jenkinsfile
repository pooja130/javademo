pipeline
{
   agent any
    stages
    {
    stage('Build')
    {
       steps
       {
            // some block
            sh 'mvn clean install'
       

        }
    }
    stage('Deploy')
    {
        steps
        {
            // some block
            sh 'sudo cp **/*.war /var/lib/tomcat8/webapps'
      
        }
    }
    }
}
