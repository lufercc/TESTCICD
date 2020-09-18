pipeline {
 agent any
 stages {
    stage("build") {
         steps {
             sh "test init"
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