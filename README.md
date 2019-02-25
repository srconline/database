# database

install pgadmin 3  from https://www.postgresql.org/ftp/pgadmin/pgadmin3/v1.22.2/win32/

GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO spidertutorial;
GRANT ALL PRIVILEGES ON ALL SEQUENCES  IN SCHEMA public TO spidertutorial;
GRANT ALL PRIVILEGES ON ALL FUNCTIONS IN SCHEMA public TO spidertutorial;

from pgadmin 3 plugin console: run this
 \i d:/temp/dellstore2-normal-1.0.sql
 
 this db is avaible in http://pgfoundry.org/frs/?group_id=1000150&release_id=376#dellstore2-dellstore2-normal-1.0-title-content
