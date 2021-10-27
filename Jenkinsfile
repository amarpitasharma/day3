pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo "Compile SuccessFully"
            }
        }

        stage("Unit test"){
          steps {
            sh "python test.py"
          }
        }
    }
}
