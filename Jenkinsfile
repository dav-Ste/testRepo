#!/usr/bin/groovy
@Library('my-build-library')
def git = new DS.Git()


node {
  if (git.isDevelopBranch()){
    echo "*************** DEV BRANCH *******************"
  }

}
