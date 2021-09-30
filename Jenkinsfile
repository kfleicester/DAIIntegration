pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Build starting'
            }
        }

        stage('Run Tests'){
        steps {
	echo 'Starting DAI Runner...'
	    sh 'chmod +x DAIrunner'
            sh './DAIrunner -v testcase http://192.168.214.140:8000/ philippa.merrill@eggplantsoftware.com xSQ6fHd6Zm8m TESTCASE1 DAITest JenkinsIntegration PhilippaCloud1 JenkinsIntegration.suite'
        }
    }
    
}
}

