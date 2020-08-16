pipeline{
    agent any
    tools {
        maven 'DEFAULT_MAVEN'
    }

    stages('Build'){
        steps{
            cmd 'mvn clean package '
            cmd 'pringenv'
        }
    }
}