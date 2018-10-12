pipeline{
    agent {
        docker { image 'citizenstig/jenkins-slave-python' }
    }
    
    
    stages {
        stage ("First Print"){
            steps{
                sh "python print.py"
            }
        }
        stage ("Second Print"){
            steps{
                sh "python print_2.py"
            }
        }
    }
}
