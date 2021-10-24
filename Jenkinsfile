pipeline {
    agent any
    parameters{
	    string(name:'Greeting', defaultValue: 'Hello', description: 'How shoild I greet the world?')
	}
    stages {
        stage('Build') {
            steps {
                bat 'echo "${params.Greeting} World"'
                bat '''
                    echo "Multiline shell steps works too"
                '''
            }
        }
    }
}
