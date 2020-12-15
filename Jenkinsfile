pipeline {
    agent { any
    stages {
        stage('build') {
            steps {
		sh 'echo "Hello world"'
                sh 'python --version'
		sh '''
			echo "multiline shell steps work too"
			ls -lah
		   '''
            }
        }
    }
}
