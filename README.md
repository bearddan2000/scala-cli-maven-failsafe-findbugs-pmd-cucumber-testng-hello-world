# scala-cli-maven-failsafe-findbugs-pmd-cucumber-testng-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testNg
and cucumber framework with surefire-findbugs
and pmd, failsafe plugins.

## Tech stack
- scala
- maven
	- findbugs
  - testNg
  - failsafe
  - surefire
  - cucumber
  - PMD

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Build concept](https://github.com/citrusframework/citrus-samples/blob/main/samples-junit/sample-junit5/pom.xml)
- [PMD example](https://github.com/eugenp/tutorials/blob/master/static-analysis/src/main/resources/logback.xml)
