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
                echo env.BRANCH_NAME
                echo 'env.BUILD_NUMBER'
                echo 'env.BUILD_ID'
                echo 'env.BUILD_DISPLAY_NAME'
                echo 'env.JOB_NAME'
                echo 'env.JOB_BASE_NAME'
                echo 'env.BUILD_TAG'
                echo 'env.EXECUTOR_NUMBER'
                echo 'env.NODE_NAME'
                echo 'env.NODE_LABELS'
                echo 'env.WORKSPACE'
                echo 'env.JENKINS_HOME'
                echo 'env.JENKINS_URL'
                echo 'env.BUILD_URL'
                echo 'env.JOB_URL'
            }
        }
    
    }
}