pipeline{
    agent any
    stages{
        stage ('Build'){
            steps{
                echo "Etapa BUILD no disponible"
            }
        }
        stage ('Test'){
            steps{
                echo "Etapa TEST no disponible"
            }
        }
        stage ('Deploy'){
            steps{
                sh "docker-compose down -v"
                sh "docher-compose up -d --build"
            }
        }
    }
}