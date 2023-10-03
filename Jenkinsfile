// Declarative //
pipeline {
    agent any

    stages {
        stage('compiling job') {
            steps {
                echo 'Compiling..'
            }
        }
        stage('test job') {
            steps {
                echo 'Testing..'
            }
        }
        stage('package job') {
            steps {
                echo 'Packaging....'
            }
        }
    }
}
// Script //
node {
    stage('compiling job') {
        echo 'Compiling....'
    }
    stage('test job') {
        echo 'Testing....'
    }
    stage('package job') {
        echo 'Packaging....'
    }
}
