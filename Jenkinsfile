#!/usr/bin/groovy
// Declarative pipeline; Each stage directive needs a steps directive.
pipeline {
  agent any

        environment {
                //PYTHONPATH = "${WORKSPACE}/section_4/code/cd_pipeline"
                ex5Quest1Repo = "handsonjenkins_ex5"  
        }

  stages {
    stage('Build') {
        steps { buildApp() }
    }
    


  } //stage definitions
}  // pipeline

    def buildApp() {
        sh "echo Building..."
    }