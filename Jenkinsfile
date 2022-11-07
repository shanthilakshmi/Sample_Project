node {
    stage('Clean Repo'){
        sh 'rm -rf Sample_Project'
    }
    stage('checkout'){
        sh 'git clone https://github.com/shanthilakshmi/Sample_Project.git'
    }
    stage('clean') {
        dir("Sample_Project")
            {
                sh 'mvn clean'
            }
    }
    stage('compile test package') {
        dir("Sample_Project")
            {
                sh 'mvn install package'
            }
    }
}
