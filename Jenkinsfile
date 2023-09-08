pipeline{
    agent any
    tools{
        maven M2_HOME
    } 
        stage('maven install'){
            steps{
                sh 'mvn install'
                
            }
        }
        stage('maven package'){
            steps{
                sh 'mvn package'
            }
        }
       
    }
}