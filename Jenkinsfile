node {
	stages {
		stage("Clone") {
			steps {
				sh "git clone git@github.com:xvelx/Hello-J.git"
				sh "javac HelloJ.java"
				sh "java HelloJ.class"
			}
		}
	}
}
