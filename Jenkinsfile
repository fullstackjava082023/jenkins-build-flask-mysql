pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Checkout from GIt') {
            steps {
                git branch: 'jenkins-docker', url: 'https://github.com/fullstackjava082023/FLASK-CONTACTS-DEVOPS'
            }
        }
    }
}
