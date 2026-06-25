pipeline {

    agent any
 
    stages {
 
        stage('Build') {

            steps {

                sh 'echo "Build Successful"'

            }

        }
 
        stage('Deploy') {

            steps {

                sh '''

                sudo mkdir -p /var/www/html

                sudo cp -r * /var/www/html/

                '''

            }

        }

    }

}
 
