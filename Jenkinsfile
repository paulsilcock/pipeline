node {
	stage("blah") {
		echo "Check out code"
		checkout scm

		sh script: "ls -l"
    }

	stage("Test approval") {
		input "Ok?"
	}
}
