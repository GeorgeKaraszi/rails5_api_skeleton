# NOTE: THIS IS A Rails 5 API setup
# README

Rails Version:

* 5.0.1 api

Ruby Version:

* 2.3.3 (soon to be 2.4 once Rails 5.1 comes)


Project settings file:

* Redo all `*.example.yml` to `*.yml` files

Environment Variables:

* Rename `.env.example` to `.env.[ENV_NAME]`

Database information:
* Database used is Postgres 9.5.3


Travis info:

* Each core `*.example.*` file is copied over using the `/bin/setup` command
    * IE: When travis runs: `database.yml.example` is copied to `database.yml` and runs those default settings


This has been pre-configured with RSPEC setup.


## Style guides

Includes a pre-configured 
* CSS Linter
* JS Linter
* RuboCop
* CodeClimate
* RVMC file
