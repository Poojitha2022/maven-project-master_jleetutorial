pipeline  {
  agent any
  stages  {
     stage("validate")  {
      steps  {
         script  {
            bat  "mvn validate"
            echo "Validation Completed"
            }
          }
        }
     stage("compile")  {
      steps  {
         script  {
            bat  "mvn compile"
            echo "Compilation Completed"
            }
          }
        }
     stage("test")  {
      steps  {
         script  {
            bat  "mvn test"
            echo "Test Completed"
            }
          }
        }
     stage("package")  {
      steps  {
         script  {
            bat  "mvn package"
            }
          }
        }
     stage("verify")  {
      steps  {
         script  {
            bat  "mvn verify"
            }
          }
        }
     stage("install")  {
      steps  {
         script  {
            bat  "mvn install"
            }
          }
        }
     }
 }
