node {
    stage('clone') {
        git 'https://github.com/hubabdou/jenkins-helloworld.git' 
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
