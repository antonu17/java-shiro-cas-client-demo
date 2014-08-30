java-shiro-cas-client-demo
==========================

Demo using the CAS client from the Shiro project (in Java) to protect a web application.

Using **mvn clean compile jetty:run**, the webapp is started on **http://localhost:8080**. The url 'protected/index.jsp' is protected and should trigger a CAS authentication.

Most of the configuration is defined in the **src/main/resources/shiro.ini** file. Use your own CAS in the cloud server

The logout is performed by calling the **http://localhost:8080/logout** url from the browser.

==

D�mo utilisant le client CAS du projet Shiro (en Java) pour prot�ger une application web.
En utilisant **mvn clean compile jetty:run**, le site web est lanc� sur **http://localhost:8080**. L'url 'protected/index.jsp' est prot�g�e et d�clenche une authentification CAS.

L'essentiel de la configuration est d�fini dans le fichier **src/main/resources/shiro.ini**. Utilisez votre propre serveur CAS in the cloud

La d�connexion est fa�te en appelant l'url **http://localhost:8080/logout** depuis le navigateur.
