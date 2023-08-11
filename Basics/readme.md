# Basics
This section contains the syntax and notes for the Basics of Postgres, including connections and executions.

## Connect Postgres on Command Line
Here is the code to connect to Postgres, when it is hosted locally or via Docker at Port 5432.

```
psql -h localhost -p 5432 -U postgres -d database_name
```

## Database
After you have connected to Postgres, you may use this code to change your desired database.

```
\c [database_name]
```

## Executing SQL queries
Simply write a SQL in the command line after you have connected to Postgres. You must finish the SQL query with <b>;</b>. For example:

```
select * from [schema_name.example_table];
```

### Executing SQL Scripts on Command Line
Coming Soon...