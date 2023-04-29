# Changelog

This changelog document contains all the notable changes made to the [CLI-RPG] project, separated by the person responsible for the change and the type of change.


<br >

## Udrescu Alexandra
### Added
- `Authentication Database` service using the `Mongo` image
- `Authentication Database Explorer` service using the `MongoExpress` image
- `Authentication` service using `Python` and the `Flask` library
- `Dockerfile` for the `Authentication` serivce
- Basic `docker-compose` file for starting new containers with the necessary services
- Basic `Grafana` functionality


<br >

<hr/>

## Cretu Andrei

### Added
- basic `REACT` project
  - 1 `REACT` page for login
  - 1 `REACT` page for choosing a new game or loading a saved one
  - 1 `REACT` page for the game itself
- `Dockerfile` for creating the project's image
- `docker-compose` file for checking the functionality


<br >

<hr/>

## Udubasa Mihai

### Added
- main `HTTP Request` handlers for `Business Logic` service

### Fixed
- database services names, so that the `Authenctication` and `IO` do not create conflicts
- `docker-compose` file name, so that it is in accordance to the default name
- conflicts between naming conventions in the repositories
- `.gitignore` file to not include logging files / entries from `Grafana`

### Changed
- the `docker-compose` files into a single one, that contains all the necessary services for running the entire project
- the `Github` repositories hierarchy, so that all the repositories for all the necessary services refer to a main repository

<br >

<hr/>

## Petre-Antica Eduard-Dominic

### Added
- `Business Logic Database` service using the `Mongo` image
- `Business Logic Database Explorer` service using the `MongoExpress` image
- repositories to the company
- basic implementation for the `Business Logic` service, using `Python` and `Flask`
- basic implementation for the `IO` service, using `Python` and `Flask`
- `docker-compose` file for running containers for the `Business Logic` and `IO` services
- `Dockerfiles` for the `Business Logic` and `IO` services
### Fixed
- communication between `Business Logic` and `IO` services
- communication between `IO` and `Business Logic Database` services
- `.gitignore` file to not include logging files / entries from the database

[CLI-RPG]: https://github.com/CLI-RPG/CLI-RPG