pipeline {
   agent any
           // label 'jenkins-slave-jnlp'
 stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too from branch test1"
                    ls -lah
                    echo "Again Hello from Test1"
                '''
            }
        }
    }
}
