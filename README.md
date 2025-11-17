# Apache Jackrabbit WebDAV For Jakarta EE

This project aims to build and deploy the libraries Apache Jackrabbit JCR Server and 
Jackrabbit WebDAV (as well as their Jackrabbit dependencies) for Jakarta EE in order to be used by Silverpeas.

The project generate an uber jarfile with Apache Jackrabbit JCR server, Apache Jackrabbit 
WebDAV and their dependencies on other Apache Jackrabbit libraries. Are excluded their 
dependencies on external libraries like:

* Tika Core
* Apache Commons File Uploads
* Apache Common Collection 4
* Apache HTTP Component Clients and Core
* SL4J

These dependencies are used and hence provided by Silverpeas. 