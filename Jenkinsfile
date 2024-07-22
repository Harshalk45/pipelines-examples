pipeline{
    agent any
    stages{
         
         stage("compile"){
            sh'javc Test.java'
         }
         stage("run"){
            sh"java Test"
         }
    }
}