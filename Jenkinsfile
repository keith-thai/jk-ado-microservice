//node {
//	stage('Build') {
//		echo "Build"
//	}
//	stage('Test') {
//		echo "Test"
//	}
//	stage('Integration Test') {
//		echo "Test"
//	}
//}

//Scripted
//node {
//    echo "Build"
//    echo "Test"
//    echo "Integration Test"
//}

//Declarative
pipeline {
    agent any
    stages {
        steps ('Build') {
            echo "Build"
        }
        steps ('Test') {
            echo "Test"
        }
        steps ('Integration Test') {
            echo "Integration Test"
        }
    }
}
