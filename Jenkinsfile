pipeline {
 agent any
 stages {
    stage("build") {
         steps {
            def gradleHome = tool 'gradle4'
            echo "''${gradleHome}'"
            sh "'${gradleHome}/bin/gradle' clean executeFeatures"
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