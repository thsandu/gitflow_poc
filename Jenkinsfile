node {
   stage("Checkout") {
    checkout scm
      sh "printenv | sort"
   }

   stage("do some important testing"){
      echo "This is the last commit: ${env.COMMIT_ID}" 
      sleep(5)
   }
}
