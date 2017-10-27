node {
    def mvnHome = tool 'Maven_3.3.9'

    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh "${mvnHome}/bin/mvn -B package"
    }
}