### Dict Java Servlet

ref: 
* https://github.com/monikaUPF/PraatontheWeb
* https://github.com/praat/praat

---

* The Project modify to the maven
---
#### Requirements:
* Java 8
* Tomcat 8x , you need your tomcat configuration
* praat
  
##### Tomcat
* /opt/tomcat/conf/tomcat-users.xml
```xml 
<!--  user manager can access only manager section  -->
<role rolename="manager-gui"/>
<user username="manager" password="admin" roles="manager-gui"/>
<!--  user admin can access manager and admin section both  -->
<role rolename="admin-gui"/>
<user username="admin" password="admin" roles="manager-gui,admin-gui"/>
```

* Intellij IDE 
Add new running configuration and select tomcat8x