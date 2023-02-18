mongosh --port 30001 --eval "rs.initiate({
 _id: \"rs0\",
 members: [
   {_id: 0, host: \"mongo1:30001\"},
   {_id: 1, host: \"mongo2:30002\"},
   {_id: 2, host: \"mongo3:30003\"}
 ]
})"

<!-- ## MongoDB source -->
<!-- docker exec -it mongodb-1 /bin/bash -->

<!-- mongosh --host mongo3 --port 30003 -->
<!-- mongosh --host mongo2 --port 30002 -->
<!-- mongosh --host mongo1 --port 30001 -->

<!-- ## Postgres sink -->
<!-- docker exec -it pg-db bash -->
<!-- psql -h pg-db -p 5439 -U postgres -W-->
<!-- createdb -h pg-db -p 5439 -U postgres test -->

<!-- Kết nối thẳng khi dùng tk root -->
<!-- psql -U postgres -->

<!-- system: PostgresSQL 
     server: pg-db:5439
     username: postgres
     password: pw123
     database: -->