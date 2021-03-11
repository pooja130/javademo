pipeline
{
   agent any
    stages
    {
    stage('Build')
    {
       steps
       {
            sh 'mvn clean install'
        }
    }
    stage('Deploy')
    {
        steps
        {
            sh 'mv target/*.war javademopipe.war'
            sh 'sudo cp javademopipe.war /var/lib/tomcat8/webapps'
        }
    }
    }
}
