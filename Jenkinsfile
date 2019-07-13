pipeline{
    agent any
         stages{
             stage (initial) {
                  steps{
                echo 'This is Srikanth !!!'
                       }
                  }
                  stage (compile) {
                       steps{
                            input ('Do you want to proceed ?')
                            }
                       }
             stage (third) {
                 when {
                     not {
                           branch 'master'
                         }
                      }
                       steps{
                            echo "Hello Finally !!!"
                            }
                       }
         }
}
