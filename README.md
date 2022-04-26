# go-ci-example

This repository contains a sample go project with unit tests and a GitHub workflow.

# Features
The CI workflow contains the following steps:
* Checkout source code
* Set up Go
* Show go version
* Print working directory
* Create artifact directory
* Build
* Show build
* Run unit tests
* Upload artifact

# Usage
The CI is designed for a Linux host runner. If a Windows Host Runner is required, minor adjustments must be made in the workflow. 

This CI example can be used as a blueprint for other Go projects.

# References
* [GitHub Actions](https://docs.github.com/en/actions)
* [Workflow syntax for GitHub Actions](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
* [GitHub Actions: About continuous integration](https://docs.github.com/en/actions/automating-builds-and-tests/about-continuous-integration)
* [How to test your Go code with Github actions](https://gfgfddgleb.medium.com/how-to-test-your-go-code-with-github-actions-f15881d46089)