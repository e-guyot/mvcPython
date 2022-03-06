FROM postgres:latest
ENV POSTGRES_PASSWORD=secret
ENV POSTGRES_USER=username
ENV POSTGRES_DB=database
COPY /database/create_fixtures.sql /docker-initdb.d/create_fixtures.sql

# docker run -it <image_id> bash
# Enter to the database
# psql postgres://username:secret@localhost:5432/database
