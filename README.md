# ip2config & ip2nationcountries

This module holds the SQL information to populate the `ip2config` & `ip2nationcountries` tables in your auth database.

The data is gathered from http://www.ip2nation.com/ip2nation

## Import into database

There are two alternatives to import this into your auth database, either manually or using the DB assambler.

### Manually

You can download the SQL files and manually import them from https://github.com/UPDATE/PATH/tree/master/sql/auth

### DB assambler

You can also follow the normal procedure of using modules by installing it in your `azerothcore-wotlk/modules/` directory and then importing them by running the
DB assambler to using `customs` or `import-customs` options.

NOTE: You do not need to reconfigure the project with this module as it does not add any sourcefiles.
