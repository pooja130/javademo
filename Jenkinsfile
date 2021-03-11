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
        dir('SpringMVCSecurityXML/target') 
       {
            // some block
            sh 'sudo cp SpringMVCSecurityXML.war /var/lib/tomcat8/webapps'
       }
        }
    }
    }
}
