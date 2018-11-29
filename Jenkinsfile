node {
	stages {
		stage("Clone") {
			steps {
				sh "javac HelloJ.java"
				sh "java HelloJ.class"
			}
		}

		stage("Clean") {
			steps {
				sh "rm HelloJ.class"
			}
		}
	}
}
