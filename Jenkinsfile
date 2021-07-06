pipeline {
     agent any
     tools {nodejs "Node LTS"}
     stages {
        stage("Build") {
            steps {
                nodejs('Node LTS') {
                    sh "sudo node -v"
                    sh "sudo npm -v"
                }
            }
        }
    }
}