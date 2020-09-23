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
        step ('Build') {
            echo "Build"
        }
        step ('Test') {
            echo "Test"
        }
        step ('Integration Test') {
            echo "Integration Test"
        }
    }
}
