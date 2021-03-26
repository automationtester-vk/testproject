#!groovy
import groovy.json.JsonSlurper

pipeline{
    agent any
    
    stages{
        stage ('Clean WorkSpace Directory'){
            steps {
                //define the single or multiple step
                bat 'echo CleanUp Stage'
            }
        }
        stage ('Git CheckOut'){
            steps {
                bat 'echo Git Checkout'
                
            }
            
        }
        stage ('Build'){
            steps {
                bat 'echo Build'
                
                
            }
        }

        stage ('Run the Test') {
            steps {
                 //define the single or multiple step
                bat 'echo Test Execution Started'
                
        }
    }
    
}
}
