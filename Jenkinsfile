node {
	stage("blah") {
		echo "Check out code"
		checkout scm

		echo "Publish HTML"
		publishHTML (target: [
	      allowMissing: false,
	      alwaysLinkToLastBuild: false,
	      keepAll: true,
	      reportDir: "knockout-d3-bindings",
	      reportFiles: "*.html, *.js, Scripts/*.js, Scripts/d3/*.js",
	      reportName: "Blah"
	    ])
	}

	stage("Test approval") {
		input "Ok?"
	}
}
