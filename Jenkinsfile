pipeline {
    agent any
    stages {
        stage("Start") {
            steps {
                bat "echo Start >> tmp.txt"
            }
        }
        stage("Running") {
            steps {
                bat "echo Running >> tmp.txt"
            }
        }
        stage("End") {
            steps {
                bat "echo End >> tmp.txt"
            }
        }
    }

}
