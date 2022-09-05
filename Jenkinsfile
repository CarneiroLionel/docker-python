node {
	def app
	
	stage('Clone Repo') {
		/* Making sure the repo is cloned */

		checkout scm
	}

	stage('Build image') {
	
	app = docker.build("carneirolionel/docker-python")	

	}
}
