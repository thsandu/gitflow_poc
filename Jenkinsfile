node {
   stage("Checkout") {
    checkout scm
   }

   stage("do some important testing"){
       sleep(10)
   }
   stage("push to master") {
        sh "printenv | sort"
    }
}