pipeline {
	agent {
		dockerfile true
	}
	stages {
		stage('docker build') {
            steps {
                dir('/teesstt/abcd_app/src/main/docker/base/'){
                    script{
                        dockerImage = docker.build("imageName")
                    }
                }
            }
        }
		
	}
}