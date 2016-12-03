node { // <1>
    stage('Checkout') { // <2>
        checkout scm
        sh 'ls'
    }
    stage('Build') { 
        sh 'docker build .'
        sh 'sleep 120'
    }
}
