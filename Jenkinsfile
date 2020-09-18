pipeline {
 agent any
 tools {
    gradle "gradle"
 }
 stages {
    stage("build") {
         steps {
             sh 'gradle --version'
         }
    }
     stage("test") {
         steps {
             sh 'gradle clean executeFeatures'
         }
     }
     stage("deploy") {
         steps {
             echo "deploy application"
         }
     }
 }
}