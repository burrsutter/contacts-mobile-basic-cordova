A) contacts-mobile-basic-services is a Maven-based Java EE 6 backend 

B) contacts-mobile-basic-client is a JBoss Hybrid Mobile Tools Apache Cordova Project

You deploy A before B

When A is deployed on an localhost EAP 6, you should have the following available:
http://localhost:8080/contacts-mobile-basic-services/rest/members

The client app exercises:
GET
PUT
POST
and DELETE

