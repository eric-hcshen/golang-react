docker run --name ostgres -p 5432:5432 -e POSTGRES_PASSWORD=postgres -d postgres

docker run -it --rm --network postgres-network postgres psql -h postgres -U postgres

[Practice](https://letscode.blog/2021/06/25/react-gin-blog-9-19-hashing-password/)