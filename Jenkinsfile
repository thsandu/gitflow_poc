node {
   stage("Checkout") {
    checkout scm
      sh "printenv | sort"
     withCheckout(scm) {
       echo "GIT_COMMIT is ${env.GIT_COMMIT}"
    }
   }

   stage("do some important testing"){
      echo "This is the last commit: ${env.COMMIT_ID}" 
      sleep(5)
   }
}
