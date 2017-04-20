#!/usr/bin/groovy

node {
  
  checkout scm

  println "Hello, world!"

  stage ('compile and test') {
    println "testing"
  }

  stage ('build') {
    println "build"
  }

  println env.BRANCH_NAME

  if (env.BRANCH_NAME == 'master') {
    stage ('deploy') {
      println "deploying"
    }
  }

}
