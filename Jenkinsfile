pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                bat 'mvn -Dskiptests clean package'
            }
        }
         stage("Test"){
            steps{
                bat 'mvn test'
            }
        }
    }
}
