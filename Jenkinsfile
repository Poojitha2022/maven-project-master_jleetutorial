pipeline  {
  agent any
  stages  {
     stage("validate")  {
      steps  {
         script  {
            bat  "mvn validate"
            }
          }
        }
     stage("compile")  {
      steps  {
         script  {
            bat  "mvn compile"
            }
          }
        }
     stage("test")  {
      steps  {
         script  {
            bat  "mvn test"
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
