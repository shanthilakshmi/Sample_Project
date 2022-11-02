node {
    stage('SCM') {
    	git clone 'https://github.com/shanthilakshmi/Sample_Project.git'
     }

    stage('clean') {
        sh label: '', script: 'mvn clean'
    }
    stage('compile test package') {
        sh label: '', script: 'mvn install'
    }
}