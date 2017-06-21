#agentCloudServer

#jetty
mvn clean jetty:run

#run swagger
http://localhost:8080/house_case_server/swagger-ui.html

#generate swagger storage doc
mvn -Dtesting -Dtest=Swagger2MarkupTest test



