pipeline {
    agent any
    stages {
        stage('stage 1') {
            steps {
                echo "hello world"
            }
        }
        stage('stage 2') {
            steps {
                echo "hello sandesh"
            }
        }
        stage('display env variables'){
            steps {
                echo ${BRANCH_NAME}
                echo '${BUILD_NUMBER}'
                echo '${BUILD_ID}'
                echo '${BUILD_DISPLAY_NAME'
                echo '${JOB_NAME'
                echo '${JOB_BASE_NAME'
                echo '${BUILD_TAG'
                echo '${EXECUTOR_NUMBER'
                echo '${NODE_NAME'
                echo '${NODE_LABELS'
                echo '${WORKSPACE'
                echo '${JENKINS_HOME'
                echo '${JENKINS_URL'
                echo '${BUILD_URL'
                echo '${JOB_URL'
            }
        }
    
    }
}