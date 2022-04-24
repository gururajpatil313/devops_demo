pipeline{
    
    agent any
    stages{
        stage('main'){
            when{
                branch 'main'
            }
            
            steps{
                echo "Building Main branch"
            }
        }
        stage('dev'){
            when{
                branch 'dev'
            }
            
            steps{
                echo "Building dev branch"
            }
        }
    }
}
