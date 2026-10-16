ppipeline{
    agent any
    
    stages{
        stage("Show parameters"){
            steps{
                echo "Select environment:${params.Environment}"
            }
            
        }
         stage("Build") {
            steps {
                bat 'echo Building app'
            }
        }
        stage("Test") {
            steps {
                bat 'echo Testing app'
            }
        }
        stage("Deploy") {
            steps {
                bat 'echo Deploy app'
            }
        }
        
    }
}
