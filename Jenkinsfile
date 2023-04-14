pipeline {
    agent any
   
    stages {
        
        
        
        stage('Deployment') {
            steps {
                sshagent(['deployment-tomcat']) {
                    sh "scp -o StrictHostKeyChecking=no /var/lib/jenkins/workspace/build_job/webapp/target/webapp.war ec2-user@3.26.42.205:/opt/apache-tomcat-9.0.73/webapps"
}
   
            }    
        }
        
    }
}    
    
                
            
        
      

    
            
           


