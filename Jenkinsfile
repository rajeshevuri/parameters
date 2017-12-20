pipeline {
    agent any
    parameters {
        string(name: 'PERSON' , defaultValue: 'Mr Jenkins' , description: 'Who should I say hello to?')
        booleanParam(name: 'DEBUG_BUILD', defaultValue: true, description: '')   
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
