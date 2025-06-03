FROM mysql:8.0.1
RUN echo "[client]" >> /etc/mysql/my.cnf 
RUN echo "skip-ssl" >> /etc/mysql/my.cnf 
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
ADD scripts/*.sql  /docker-entrypoint-initdb.d