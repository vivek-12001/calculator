pipeline {
     agent any
     stages {
        stage("Build") {
            steps {
                sh "sudo npm install"
                sh "sudo npm run build"
            }
        }
        stage("Build") {
            steps {
                sh "sudo npm run test -- --watchAll=false"
            }
        }
    }
}
