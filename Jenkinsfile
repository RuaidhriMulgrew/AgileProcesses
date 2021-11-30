pipeline { // must be top level, declarative pipeline
	
	any agent // will run on any available jenkins node

	stages { // where the work happens, stages of the pipeline

		stage("build") {

			steps {
				// here goes the script that execute commands on the jenkin's server
				echo "Building the application"
			}
		}

		stage("test") {

			steps {
				echo "Testing the application"
			}
		}

		stage("deploy") {

			steps {
				echo "Deploying the application"
			}
		}
	}
}

//node {
	// groovy script
	// same as top 2 lines.
//}

// save as .groovy
