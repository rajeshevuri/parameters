pipeline {
    agent any
    parameters {
        string(name: 'PERSON' 'GENDER', defaultValue: 'Mr Jenkins' 'Mr', description: 'Who should I say hello to?' 'select the gender')
    }  
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
