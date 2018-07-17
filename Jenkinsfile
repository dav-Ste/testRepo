#!/usr/bin/groovy
@Library('my-build-library')
def git = new ds.ci.jenkins.Git()


node {
  if (git.isDevelopBranch()){
      echo "Dev Branch"
  }
  else
  {
    echo "Not Dev Branch"
  }

}
