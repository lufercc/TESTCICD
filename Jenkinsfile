pipeline {
 agent any
 stages {
    stage("build") {
        tools {
            gradle 'gradle'
        }
         steps {
            sh "gradle clean executeFeatures"
         }
    }
     stage("test") {
         steps {
             echo 'testtestset'
         }
     }
     stage("deploy") {
         steps {
             echo "deploy application"
         }
     }
 }
}