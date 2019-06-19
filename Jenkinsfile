node {
   stage("Checkout") {
    def commit = checkout(scm).GIT_COMMIT
      echo "Das ist mein toller commit: ${commit}"
      sh "printenv | sort"
   }

   stage("do some important testing"){
      echo "This is the last commit: ${env.COMMIT_ID}" 
      sleep(5)
   }
}
