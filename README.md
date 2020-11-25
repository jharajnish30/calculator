Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/RkjOrg/jharajnish30_github/_apis/build/status/jharajnish30.calculator?branchName=master)](https://dev.azure.com/RkjOrg/jharajnish30_github/_build/latest?definitionId=11&branchName=master)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.


Now this repository is integrated with Azure Pipeline. The commit on this repo will trigger the Azure pipeline build automatically
