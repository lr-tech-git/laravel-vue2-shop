###
Mysql V8.0
db user with create db prvilieges / multitenant


## Run Project

run `make build`

run `make migrate`

import dump `./database/dump_main_db_for_developer.sql`

create db `connection_161`

run `make migrate`

run `make seed`

run `make create-test-connection`

## Commands

`make build` - up docker containers

`make down` - down docker containers

`make migrate` - run migrate for main db and tenants dbs

`make seed` - run db seeds for main db and tenants dbs

`make composer-install` - run composer install

`make test` - run tests

`make dev-deploy` - run migrations, seeds, composer install, npm install, npm run dev and artisan clear config and cache

`make prod-deploy` - run migrations, seeds, composer install, npm install, npm run prod and artisan clear config and
cache
