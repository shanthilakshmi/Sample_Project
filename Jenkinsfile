node {
    stage('checkout'){
     sh 'git clone https://github.com/shanthilakshmi/Sample_Project.git'
    }
    stage('clean') {
        sh label: '', script: 'mvn clean'
    }
    stage('compile test package') {
        sh label: '', script: 'mvn  -f https://github.com/shanthilakshmi/Sample_Project install'
    }
}
