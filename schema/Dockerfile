FROM mysql:5.7.24
ENV MYSQL_ROOT_PASSWORD Birthday30!

# Add the content of the sql-scripts/ directory to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup

COPY schema.sql /docker-entrypoint-initdb.d/