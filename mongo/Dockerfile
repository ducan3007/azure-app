FROM mongo:5.0.13

EXPOSE 27017


COPY . .


RUN mongorestore --db db_questionAnswer /dump/db_questionAnswer


CMD ["mongorestore", "--db", "db_questionAnswer", "/dump/db_questionAnswer"]