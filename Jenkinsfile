node {
    stage('clean') {
        sh label: '', script: 'mvn clean'
    }
    stage('compile test package') {
        sh label: '', script: 'mvn install'
    }
}