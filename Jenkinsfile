#!groovy
jettyUrl = 'http://localhost:8081/'

/*
stage 'Dev'
node {
    checkout scm
    mvn '-o clean package'
    dir('target') {stash name: 'war', includes: 'x.war'}
}
