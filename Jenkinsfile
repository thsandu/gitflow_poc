node {
   stage("Checkout") {
    checkout scm
   }

   stage("do some important testing"){
      echo "This is the last commit: ${env.COMMIT_ID}" 
      sleep(10)
   }
   stage("push to master") {
        sh "printenv | sort"
    }
}
