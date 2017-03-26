node {
	stage("blah") {
		echo "Check out code"
		checkout scm

		echo "Publish HTML"
		archiveArtifacts artifacts: "**.html"
    }

	stage("Test approval") {
		input "Ok?"
	}
}
