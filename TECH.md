**Docker Engine v'2.0'**

 Docker Engine is an open source containerization technology for building and containerizing your applications. 
 i decided to include this library because:
 Docker Engine acts as a client-server application with:

 -A server with a long-running daemon process dockerd.
 
 -APIs which specify interfaces that programs can use to talk to and instruct the Docker daemon.
 
 -A command line interface (CLI) client docker.

 The CLI uses Docker APIs to control or interact with the Docker daemon through scripting or direct CLI commands. 
 Many other Docker applications use the underlying API and CLI. 
 The daemon creates and manage Docker objects, such as images, containers, networks, and volumes.

### import sample data
1: install docker & docker-compose

2: download project (clone it)

3: execute this command line : docker-compose up &

4: import codflix sql init script :
          sudo docker exec -i ec-code-2020-codflix-java-master_db_1 mysql -ucodflix -pcodflix codflix < /Users/amineamara/Downloads/codflix_aminec/codflix.sql 

### import sample data
import codflix sample Data script :
   sudo docker exec -i ec-code-2020-codflix-java-master_db_1 mysql -ucodflix -pcodflix codflix < /Users/amineamara/Downloads/codflix_amine/sampleData_codflix.sql