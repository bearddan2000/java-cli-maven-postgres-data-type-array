# java-cli-maven-postgres-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

## Tech stack
- java
- maven
  - log4j
  - postgres driver

## Docker stack
- maven:3-openjdk-17
- postgres

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`

## Credit
https://github.com/htorun/dbtableprinter
