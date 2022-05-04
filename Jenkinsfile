node {
    // checkout is a step.
    // it git clone the application code.
    // whether to git clone ?
    checkout scm 

    /* .. snip .. */
    stage('Build') {
        echo 'Building....'
	steps {
		echo 'Build --- steps . . . '
		echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
	}
    }
    stage('Test') {
        echo 'Testing....'
	steps {
		echo 'Test --- steps . . . '
	}
    }
    stage('Deploy') {
        echo 'Deploying....'
	steps {
		echo 'Deploy --- steps . . . '
	}
    }
}

