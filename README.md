# Description
This repository implements automated analysis for the `sk init --demo` project using a variety 
of continuous integration services where each branch is an implementation on a given service or using a certain environment management method:

- master - no CI
- [GHA-ghpages]() - GitHub Actions where software is installed from scratch on each build (unstable) 
- [GitLab-CI](https://matthewcarlucci.gitlab.io/sk_demo_workflow_test/) - GitLab CI using a base docker image with a few extra installs

Each branch will be developed to accomodate usage with arbitrary analysis projects allowing for a variety of environment definition methods.
