node {

    withMaven(maven:'maven') {
        
        stage('Initialize'){
    
    def mavenHome  = tool 'maven'
    def docker = tool 'docker'
   
   
     }

        stage('Checkout') {
            git url: 'https://github.com/piomin/sample-spring-microservices.git', credentialsId: 'github-piomin', branch: 'master'
        }

        stage('Build') {
            sh 'mvn clean install'

        }
       

     }
      
}
