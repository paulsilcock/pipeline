node {
	stage("blah") {
		echo "Check out code"
		checkout scm

		echo "Publish HTML"
		archiveArtifacts artifacts: "**.html, **.js"
    }

	stage("Test approval") {
		input "Ok?"
	}
}
