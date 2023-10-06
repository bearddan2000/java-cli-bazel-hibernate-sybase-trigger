# java-cli-bazel-hibernate-sybase-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- bazel
  - hibernate
  - hql
  - envers
  - log4j
  - sybase driver

## Docker stack
- l.gcr.io/google/bazel:latest
- datagrip/sybase

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
