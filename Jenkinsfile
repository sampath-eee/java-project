pipeline{
    agent any
    stages{
        stage("Build"){
            step{
                sh 'mvn -Dskiptests clean package'
            }
        }
        stage("Test"){
            step{
                sh 'mvn test'
            }
        }        
    }
}
