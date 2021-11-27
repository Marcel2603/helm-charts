# Postgres
This charts provides a lightweight postgres installation.

# Configuration
You can simply run the default chart. We the default config, we will create a DB with 
the User "postgres" and a default schema "postgres". To change the default behavior, just
create a `rootAccount`-Object in the values.yaml.

## Create multiple Databases
This chart also provides the option to create multiple databases/schemas. To enable this option,
simply fill the `additionalDatabases`-Property. The format is `DB_NAME:USER,DB_NAME2:USER2`.
