## SEMOSS using postgres for metadata storage

Base postgres image with the necessary schema files defined.  See https://hub.docker.com/_/postgres for additional details/reference.

Build the image and run:
```
docker build . -t semoss_postgres
docker run -it --name semoss_postgres -p 5432:5432 -e POSTGRES_PASSWORD=password semoss_postgres
```

Remember to replace existing smss files
