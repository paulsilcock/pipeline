node {
	stage("blah") {
		echo "Check out code"
		checkout scm

		echo "Publish HTML"
		archiveArtifacts includes: "**.html, **.js"
    }

	stage("Test approval") {
		input "Ok?"
	}
}
