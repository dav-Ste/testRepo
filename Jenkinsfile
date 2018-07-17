#!/usr/bin/groovy
@Library('my-build-library')
def git = new ds.Git()


node {
  if (git.isDevelopBranch()){
    echo "*************** DEV BRANCH *******************"
  }
  else
  {
    echo "------------------- NOT DEV BRANCH -------------------"
  }

}
