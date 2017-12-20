pipeline {
    agent any
    parameters {
        string(name: 'PERSON' 'GENDER', defaultValue: 'Mr Jenkins' 'Mr', description: 'Who should I say hello to?' 'select the gender')
        booleanParam(name: 'DEBUG_BUILD', defaultValue: true, description: '')   
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
