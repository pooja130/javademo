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
            sh 'sudo cp target/example-0.0.1-SNAPSHOT.war /var/lib/tomcat8/webapps'
      
        }
    }
    }
}
