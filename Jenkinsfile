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
            sh 'mv target/*.war javademo.war'
            sh 'sudo cp javademo.war /var/lib/tomcat8/webapps'
      
        }
    }
    }
}
