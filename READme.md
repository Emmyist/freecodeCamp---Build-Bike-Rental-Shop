dump_databse - pg_dump -cC --inserts -U <username> database > <filename>.sql

restore database from dump - psql -U postgres < <filename>.sql
