# Description
This repository stores the `sk init --demo` project of [Scikick](https://github.com/matthewcarlucci/scikick) to demonstrate how projects can be configured to execute analysis from scratch after every change to the reporsitory. It uses a variety of continuous integration services where each branch is a unique implementation of automated re-execution using different services or environment management methods:

- master - no CI
- [GHA-ghpages]() - GitHub Actions where software is installed from scratch on each build (unstable) 
- [GitLab-CI](https://matthewcarlucci.gitlab.io/sk_demo_workflow_test/) - GitLab CI using a base docker image with a few extra installs

Each branch can accomodate usage with arbitrary analysis projects allowing for a variety of environment definition methods.
