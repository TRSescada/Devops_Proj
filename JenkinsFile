pipeline {
    agent any

    stages {
        stage('SCM PROJECT') {
            steps {
                echo 'Getting PROJECT FROM SCM'
                sleep(3)
            }
        }
        stage('BUILD') {
            steps {
                echo 'BUILD OF Project IN PROGRESS'
                sleep(3)
            }
        }
        stage('UNIT TEST') {
            steps {
                echo 'TEST PHASE IN PROGRESS'
                sleep(3)
            }
        }
        stage('PACKAGE & DEPLOY') {
            steps {
                echo 'PACKAGING and DEPLOYMENT IN PROGRESS'
                sleep(3)
            }
        }
        stage('UI TEST') {
            steps {
                echo 'POST DEPLOYMENT TEST PHASE IN PROGRESS'
                sleep(3)
            }
        }
        stage('ARCHIVE') {
            steps {
                echo 'ARCHIVING PHASE IN PROGRESS'
                sleep(3)
            }
        }
    }
}
