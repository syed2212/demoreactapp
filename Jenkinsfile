pipeline {
     agent any
     tools {nodejs "node"}
     stages {
        stage("Build") {
            steps {
                nodejs('Node LTS') {
                    sh "sudo npm install"
                    sh "sudo npm run build"
                }
            }
        }
    }
}