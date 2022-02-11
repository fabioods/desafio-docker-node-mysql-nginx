FROM mysql:5.7

CMD [ "--innodb-use-native-aio=0" ]

COPY people.sql /docker-entrypoint-initdb.d/