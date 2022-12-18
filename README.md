# python-web-bazel-flask-mvc-mysql-pop

## Description
Creates a datatable of `pop` for a flask project.

If path is not found, will default to 404 error.

## Tech stack
- bazel
- python
  - flask
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- mariadb

## Docker stack
- l.gcr.io/google/bazel:latest
- mariadb:latest

## To run
`sudo ./install.sh -u`
- [web-bazel app](http://localhost)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
- https://stackoverflow.com/questions/27766794/switching-from-sqlite-to-mysql-with-flask-sqlalchemy
