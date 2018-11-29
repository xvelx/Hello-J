node {
	stages {
		stage("Clone") {
			steps {
				echo "Compiling..."
				sh "javac HelloJ.java"
				echo "Running..."
				sh "java HelloJ.class"
			}
		}

		stage("Clean") {
			steps {
				echo "Removing..."
				sh "rm HelloJ.class"
			}
		}
	}
}
