#Create MySQL Image for JSP Tutorial Application
FROM mysql

ENV MYSQL_ROOT_PASSWORD test1234
COPY . /docker-entrypoint-initdb.d

EXPOSE 3306