pipeline {
    agent any

    triggers {
        githubPush()
    }       

    stages {
        stage('Print variables') {
            steps {
                echo "BUILD_DISPLAY_NAME = ${BUILD_DISPLAY_NAME}"
                echo "BUILD_ID = ${BUILD_ID}"
                echo "BUILD_NUMBER = ${BUILD_NUMBER}"
                echo "BUILD_TAG = ${BUILD_TAG}"
                echo "BUILD_URL = ${BUILD_URL}"
                echo "EXECUTOR_NUMBER = ${EXECUTOR_NUMBER}"
                echo "JENKINS_HOME = ${JENKINS_HOME}"
                echo "JENKINS_URL = ${JENKINS_URL}"
                echo "JOB_NAME = ${JOB_NAME}"
                echo "NODE_NAME = ${NODE_NAME}"
                echo "WORKSPACE = ${WORKSPACE}"
            }
        }
        stage('JENKINS VARIABLES') {
            steps {
                echo "PATH = ${PATH}"
                echo "LANGUAGE = ${LANGUAGE}"
                echo "LC_MEASUREMENT = ${LC_MEASUREMENT}"
                echo "LC_MONETARY = ${LC_MONETARY}"
                echo "LC_TELEPHONE = ${LC_TELEPHONE}"
                echo "LC_ADDRESS = ${LC_ADDRESS}"
                echo "LC_TIME = ${LC_TIME}"
                echo "LC_MESSAGES = ${LC_MESSAGES}"
                echo "TERM = ${TERM}"
                echo "LANG = ${LANG}"
                echo "JENKINS_HOME = ${JENKINS_HOME}"
                echo "LC_NUMERIC = ${LC_NUMERIC}"
                echo "LC_ALL = ${LC_ALL}"
                echo "LC_COLLATE = ${LC_COLLATE}"
                echo "LC_PAPER = ${LC_PAPER}"
                echo "LC_CTYPE = ${LC_CTYPE}"
                echo "PWD = ${PWD}"
                echo "HOME = ${HOME}"
                echo "LC_NAME = ${LC_NAME}"
                echo "LC_IDENTIFICATION = ${LC_IDENTIFICATION}"
            }
        }
        stage('GITHUB') {
            steps {
                echo "GITHUB_ACTOR = ${GITHUB_ACTOR}"
                echo "GITHUB_REPOSITORY = ${GITHUB_REPOSITORY}"
                echo "GITHUB_EVENT_NAME = ${GITHUB_EVENT_NAME}"
                echo "GITHUB_EVENT_PATH = ${GITHUB_EVENT_PATH}"
                echo "GITHUB_WORKFLOW = ${GITHUB_WORKFLOW}"
                echo "GITHUB_HEAD_REF = ${GITHUB_HEAD_REF}"
                echo "GITHUB_BASE_REF = ${GITHUB_BASE_REF}"
                echo "GITHUB_SHA = ${GITHUB_SHA}"
            }
        }
    }
}