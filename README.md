# kotlin-cli-maven-spring-failsafe-findbugs-pmd-cucumber-mockito-junit-hello-world

## Description
A POC for spring app using junit5, cucumber, mockito,
pmd, and findbugs framework with failsafe
and surefire plugins.

Findbugs and pmd analyze source code for
potential bugs.

This is a simple and trivial way to start:
  - kotlin
    - springframework
    - cucumber test runner for junit5
  - cucumber
    - parameterized scenario
  - mockito
    - integration of junit5
    - injection

## Tech stack
- kotlin
- maven
	- mockito
  - spring
  - junit5
  - cucumber
  - failsafe
  - findbugs
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
