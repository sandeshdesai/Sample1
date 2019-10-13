def name="Sandesh"
pipeline {
    agent any
    enviroment {
        BUILD_DISPLAY_NAME="Madhura"
    }
    stages {
        stage("Name" ) {
            steps {
            echo "My name is ${name}"
            }
        }
        stage('display env variables'){
            steps {
                echo "${BUILD_NUMBER}"
                echo "${BUILD_ID}"
                echo "${BUILD_DISPLAY_NAME}"
                echo "${JOB_NAME}"
                echo "${JOB_BASE_NAME}"
                echo "${BUILD_TAG}"
                echo "${EXECUTOR_NUMBER}"
                echo "${NODE_NAME}"
                echo "${NODE_LABELS}"
                echo "${WORKSPACE}"
                echo "${JENKINS_HOME}"
                echo "${JENKINS_URL}"
                echo "${BUILD_URL}"
                echo "${JOB_URL}"
            }
        }
        stage('display build variables') {
            steps {
                echo "${currentBuild.number}"
                echo "${currentBuild.result}"
                echo "${currentBuild.currentResult}"
                echo "${currentBuild.displayName}"
                echo "${currentBuild.fullDisplayName}"
                echo "${currentBuild.projectName}"
                echo "${currentBuild.fullProjectName}"
                echo "${currentBuild.id}"
                echo "${currentBuild.timeInMillis}"
                echo "${currentBuild.startTimeInMillis}"
                echo "${currentBuild.duration}"
                echo "${currentBuild.durationString}"
                echo "${currentBuild.absoluteUrl}"
            }
        }
    }
}