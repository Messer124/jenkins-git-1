pipeline {
	agent any
	parameters{
	    string(name:'Greeting', defaultValue: 'Hello', description: 'How shoild I greet the world?')
	}
	stages {
		stage('Example') {
			steps {
			    echo "${params.Greeting} World!"
			}
		}
	}
}
