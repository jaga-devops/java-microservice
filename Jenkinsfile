pipeline {
    agent any
 tools {
        maven 'local_maven'
    }

    stages {
        
        stage('eureka-server') {
            steps {
                 dir('eureka-server') {
                    sh 'mvn clean package -Dmaven.test.skip=true'
		    //sh 'docker build -t eureka-server .'

                }
            }
                
        }
		stage('api-gateway') {
            steps {
                 dir('api-gateway') {
                    sh 'mvn clean package'
		    sh 'docker build -t api .'
                }
            }
                
        }
        stage('admin-server') {
            steps {
                 dir('admin-server') {
                    sh 'mvn clean package -Dmaven.test.skip=true'
					//sh 'docker build -t admin .'

                }
            }
                
        }        
        }
    }
