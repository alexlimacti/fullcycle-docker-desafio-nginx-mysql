FROM mariadb:10.5

CMD [ "--innodb-use-native-aio=0" ]

COPY setup.sql /docker-entrypoint-initdb.d/