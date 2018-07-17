#!/usr/bin/groovy
@Library('my-build-library')
def git = new ds.Git()


node {
  if (git.isDevelopBranch()){
    echo "Dev Branch"
  }
  else
  {
    echo "NOT Dev Branch"
  }

}
