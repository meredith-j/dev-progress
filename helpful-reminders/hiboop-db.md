db -- look at prologue for db column names

if i want to use terminal to look through db stuff:
docker exec -it boop-app bash -c 'psql $PG_CONNECTION_STRING'

\d [table name] will give me the columns, data types and rows for that table

select * from [table name] will list an entire table -- best used on a desktop terminal, not vscode as vscode's terminal is tiny