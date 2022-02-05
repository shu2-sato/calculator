Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/se106work/%E5%A4%96%E9%83%A8%E3%82%BD%E3%83%BC%E3%82%B9%E7%AE%A1%E7%90%86%E3%81%A8%20Azure%20Pipelines%20%E3%81%AE%E7%B5%B1%E5%90%88/_apis/build/status/shu2-sato.calculator%20(1)?branchName=master)](https://dev.azure.com/se106work/%E5%A4%96%E9%83%A8%E3%82%BD%E3%83%BC%E3%82%B9%E7%AE%A1%E7%90%86%E3%81%A8%20Azure%20Pipelines%20%E3%81%AE%E7%B5%B1%E5%90%88/_build/latest?definitionId=32&branchName=master)
The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

