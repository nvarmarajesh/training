
pipeline{
  agent none
  stages{
    stage('test'){
       agent any
          steps {
            sh "echo this is the test for pipeline"
          
          }   
          
          }
	stage('build'){
       agent any
          steps {
          FROM ubuntu:20.04

          RUN apt update && apt install -y sbcl

          WORKDIR /usr/src 
          
          }   
          
          }
  }
  
  
}
