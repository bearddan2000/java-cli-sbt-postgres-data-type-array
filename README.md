# java-cli-sbt-postgres-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

## Tech stack
- java
- sbt
  - log4j
  - postgres driver

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10
- postgres:alpine

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
