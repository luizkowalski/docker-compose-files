# docker-compose files
Some useful docker-compose files that I use in some projects

# Postgres master/slave repl
To access the master server locally, run `docker exec -it postgres-master psql -U postgres -c "alter user postgres with password 'postgres'"`
