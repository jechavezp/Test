node {

   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git branch: 'feature/jenkinsfile', url: 'https://github.com/jechavezp/DevopsLearning'
   }

//    stage('Build') {
//       // Run the maven build
//       if (isUnix()) {
//          sh "'${mvnHome}/bin/mvn' -Dmaven.test.failure.ignore clean package"
//       } else {
//          bat(/"${mvnHome}\bin\mvn" -Dmaven.test.failure.ignore clean package/)
//       }
//    }

//    stage('Results') {
//       junit '**/target/surefire-reports/TEST-*.xml'
//       archive 'target/*.jar'
//    }
}