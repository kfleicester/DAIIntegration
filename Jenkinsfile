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
            sh './DAIrunner -v testcase https://demo.dai.eggplant.cloud/ kieran.leicester@keysight.com H4wk3y3! demoTC kieran.leicester@keysight.com demoLesson2 kierleic "/Users/kierleic/Desktop/EPF/Chapter\\ 3\\ Suite.suite"'
        }
    }
    
}
}

