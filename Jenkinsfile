pipeline {
     agent any
     tools {nodejs "Node LTS"}
     stages {
        stage("Build") {
            steps {
                nodejs('Node LTS') {
                    sh 'npm install'
                    sh 'npm run build'
                    sh 'ls'
                }
               
            }
        }
    }
}