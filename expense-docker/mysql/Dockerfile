FROM mysql:8.0.1
RUN echo "skip-ssl = on" >> /etc/mysql/my.cnf
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
ADD scripts/*.sql  /docker-entrypoint-initdb.d