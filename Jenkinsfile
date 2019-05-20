pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            parallel {
                stage('API tests') {
                    steps {
                        echo 'Building..'
                        sleep 1
                    }
                }
                stage('Cypress tests') {
                    steps {
                        echo 'Building..'
                        sleep 1
                    }
                }
                stage('Protractor tests') {
                    steps {
                        echo 'Building..'
                        sleep 1
                    }
                }
                stage('Integration tests on Windows') {
                    steps {
                        echo 'Building..'
                        sleep 1
                    }
                }
                stage('Integration tests on Linux') {
                    steps {
                        echo 'Building..'
                        sleep 1
                    }
                }
            }
        }
        stage('Build documentation') {
            steps {
                echo 'Deploying....'
                sleep 1
            }
        }
        stage('Upload package') {
            steps {
                echo 'Deploying....'
                sleep 1
            }
        }
    }
}