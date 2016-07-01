#!groovy

stage 'Dev'
node {
    checkout scm
    mvn deploy
    dir('target') {stash name: 'war', includes: 'x.war'}
}
