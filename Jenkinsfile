#!/usr/bin/env groovy

/*
 * Jenkinsfile for testing Sumo Logic plugin
 */
pipeline {
    agent any 
    options {
        SumoPipelineLogCollection()
    }
    stages {
        stage('build') {
            steps {
                echo 'Building'
            }
        }
        stage('unit-test') {
            steps {
                echo 'Testing' 
            }
        }
        stage('package') {
            steps {
                echo 'Packaging' 
            }
        }
        stage('deploy-to-qa') {
            steps {
                echo 'Deploying to QA' 
            }
        }
        stage('ui-tests') {
            steps {
                echo 'Runing UI Tests' 
            }
        }
        stage('deploy-to-stage') {
            steps {
                echo 'Deploying to Staging' 
            }
        }
        stage('performance-tests') {
            steps {
                echo 'Running performance tests' 
            }
        }
        stage('deploy-to-production') {
            steps {
                echo 'Deploying to Production' 
            }
        }
    }
}