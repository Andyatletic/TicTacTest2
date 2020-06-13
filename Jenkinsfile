pipeline {
tools {
 maven "M3"
}
agent any
stages {
 stage("Preparation") {
	 steps {
	 	git 'https://github.com/Andyatletic/TicTacTests.git'
	 }
	}
	stage("Test") {
	 steps {
	 sh "mvn test"
	 }
	 }
	}
}  