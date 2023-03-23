pipeline {
	stages {
		stage('docker build') {
            steps {
                    script{
					echo "Building Docker Image"
                    dockerImage = docker.build("imageName:latest -f ./teesstt/abcd_app/src/main/docker/base/")
                }
            }
        }
    }
		
}