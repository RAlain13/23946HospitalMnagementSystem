# 23946Hospital-Management-System-Project (HMS)
Project on Hospital sector which is covering various field of this 3 sector.This project is using Spring Framework, Hibernate, JPA, Rest, JSP.

# Docker Integration

# Docker deployment 
## Requirements

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.medical.SpringMVC` class from your IDE.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```

## Deploying the application to OpenShift

The easiest way to deploy the sample application to OpenShift is to use the [OpenShift CLI](https://docs.openshift.org/latest/cli_reference/index.html):

```shell
oc new-app soumyadip007/E-Medical-System-Web-Project-Using-Spring-Boot-Security-MVC-Hibernate-JPA-Rest-Thymeleaf-HQL
```

This will create:

* An ImageStream called "springboot-maven3-centos"
* An ImageStream called "springboot-sample-app"
* A BuildConfig called "springboot-sample-app"
* DeploymentConfig called "springboot-sample-app"
* Service called "springboot-sample-app"

If you want to access the app from outside your OpenShift installation, you have to expose the springboot-sample-app service:

```shell
oc expose springboot-sample-app --hostname=www.example.com
```

![1](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/1175db45-fa1d-4f55-a9d1-17b71a53d8e3)

# User Panel :

![2](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/c5839376-bbbb-4363-9877-264bdaf3972b)
![3](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/5303c90d-c49c-4c2e-8eb4-cde6b3608384)
![4](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/50edd40f-0b54-4afe-b96f-e8b13cc511ae)
![5](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/11604d78-a52d-4943-9a73-5f65a831ea32)
![6](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/c67d041a-de90-4861-825e-78367dc64352)
![7](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/46b7d819-8887-4d66-a0a5-eb9026f0d60a)
![8](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/0df49c43-d94b-4627-b1b0-948dd8a933e1)
![9](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/37df6401-4783-4a57-8752-882a338b3b82)
![10](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/d144f328-1cbb-4d16-a8b5-c34edfa79205)
![11](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/e7668ea4-e143-4d8a-bd51-1bc5b5385fc8)
![12](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/cc0f3df8-a2ba-4e17-aa6e-1f149de87556)

# Doctor Panel (Dashboard Access):


![13](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/54c07336-6e65-4c05-8247-e306e5af534f)
![14](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/31b1533d-d65c-4934-8ce4-a5cbd7bbd223)

# Master Admin Panel (Dashboard Access):

![15](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/45ffa73b-eca7-4562-bb92-af74f8fa7dec)
![16](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/ff3b6bf2-87b9-4a07-a80e-2d5e65a381aa)
![17](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/3add7f58-d478-4e5b-8c73-409730bc049c)
![18](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/2e91b15a-616c-4ddf-a65b-9022a3cabcbc)
![19](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/ff933abb-ab0a-4a33-874e-7b3ce1f81f2a)
![20](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/158ff638-ee66-4a66-a5a2-7c95af5accb8)
![21](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/d0974353-2af3-427c-9447-56724c9744b2)
![22](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/7f714188-7d6d-4326-89ba-beb52d486a2a)
![23](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/015423bc-6e58-4804-a34e-24f54079b816)


## Copyright @soumyadip007
```shell
/**
 * 
 * @author Soumyadip Chowdhury
 * @github soumyadip007
 *
 */

```
Released under the Apache License 2.0. See the [LICENSE](https://github.com/codecentric/springboot-sample-app/blob/master/LICENSE) file.
# #Java Software (AWT/Swing/JavaFx/JDBC)

- [Java Swing 4 Projects Book selling system,Stadium Management,Chatbot etc](https://github.com/soumyadip007/Java-JavaFx-Swing-Projects-Desktop-Application-GUI-Software)

- [School Management System Software](https://github.com/soumyadip007/School-Management-System-GUI-Software-Using-Java-Swing-AWT-JDBC-JTatoo-MySql)

- [Java Swing Complete tutorial with example for JavaGuides.net](https://github.com/soumyadip007/Java-Swing-tutorials-and-examples-for-JavaGuides.net)


# #J2EE (JSP/Servlet/JSTL/JDBC Projects)

- [E-Market Place OLX-Clone](https://github.com/soumyadip007/E-Marketplace-for-buying-and-reselling-products-Web-Project-Using-JSP-Servlet-Jstl-Security-Jdbc)

- [Startup Company Live Website](https://soumyadip007.github.io/Coding_Liquids-StartUp-Company-Live-Website-Using-JSP-Servlet-JSTL-Security-JDBC-MD5-MySql-Bootstrap/)

- [Post-Disaster Management & Women Safety Project](https://github.com/soumyadip007/Post-Disaster-Management-and-Women-safety-Hackathon-JSP-Servlet-MySql-Bootstrap-GoogleMapApi-OSM)

- [Aim-India-Foundation-NGO-Live-Website](Aim-India-Foundation-WebDev-Internship-Using-Jsp-Servlet-Jstl-Jdbc-MySql-Bootstrap)

- *https://Lightningspeedmatchmaker.com* (in Private repo for security/commercial purposes,USA project)


# #Spring & Hibernte (Codes & Projects)

- [Spring-Core-XML-Data-Dependency-BeanScope-BeanLifecycle](https://github.com/soumyadip007/Spring-Core-XML-Data-Dependency-BeanScope-BeanLifecycle)

- [Spring-Core-Annotation](https://github.com/soumyadip007/Spring-Core-Annotation-BeanScope-BeanLifecycle)

- [Hibernate-ORM (All)](https://github.com/soumyadip007/Hibernate-ORM-Entity-Relations)

- [Spring-MVC-Request-Mapping-Validation](https://github.com/soumyadip007/Spring-MVC-Request-Mapping-Validation)

- [Customer-Tracker-CURD-Application-Using-Spring-MVC-Hibernate (Mini-Project)](https://github.com/soumyadip007/Customer-Tracker-CURD-Application-Using-Spring-MVC-Hibernate)

- [Spring-Security-User-Login-Authentication-Application-JDBC-Bcrypt](https://github.com/soumyadip007/Spring-Security-User-Login-Authentication-Application-JDBC-Bcrypt)

- [Spring-Security-Authentication-System-Registration-Login-with-OTP-Token-and-Email-verification (Mini Project)](https://github.com/soumyadip007/Spring-Security-Authentication-System-Reg-Login-with-OTP-Token-and-Email-verification)

- [SpringRest-Restfull-Webserices-Jackson-Json-Data-Binding-MVC](https://github.com/soumyadip007/Spring-Rest-Jackson-Json-Data-Binding)

- [Customer-Relationship-Management-Real-time-CURD-Application-using-Spring-Rest-Json-HQL-WebServices-MVC (Mini Project)](https://github.com/soumyadip007/Customer-Relationship-Management-Real-time-CURD-Application-using-Spring-Rest-Json-HQL-WebServices)

- [Spring-Boot-with-Restfull-Webservices-Json-Hibernate-JPA-Spring-Data](https://github.com/soumyadip007/Spring-Boot-with-Rest-Json-Hibernate-JPA-SpringDataJPA)

- [Employee-Relationship-CURD-Application-using-Spring-Boot-Thymeleaf-Hibernate-JPA-MVC (Mini Project)](https://github.com/soumyadip007/Employee-Relationship-CURD-Application-using-Spring-Boot-Thymeleaf-Hibernate-JPA-MVC)

- [E-Medical-System (Project)](https://github.com/soumyadip007/E-Medical-System-Web-Project-Using-Spring-Boot-Security-MVC-Hibernate-JPA-Rest-Thymeleaf-HQL)

- [SpringBoot-Angular8-Login-Registration](https://github.com/soumyadip007/SpringBoot-Angular8-Login-Registration-for-JavaGuides.net)

- *Pujo Direction* (Android/WEB(Spring Boot, MVC, REST, Security, Hibernate, JPA, Thymeleaf) http://pujodir.cloudjiffy.net/Pujo-Direction(App Store)) (in Private repo for security purposes)

# #Angular8 (Codes & Projects)

- [Angular8-Data-Event-Binding-Directives-Pipes-Form-Validation-Security-HTTP-Service-Routing](https://github.com/soumyadip007/Angular-8-Data-Event-Binding-Directives-Pipes-Form-Validation-Security-HTTP-Service-Routing)

- [Angular-Firebase-CURD-Application](https://github.com/soumyadip007/Angular-Firebase-CURD)

- [Angular8-Authentication-and-Authorization-JSON-JWT (Security)](https://github.com/soumyadip007/Angular-8-Authentication-and-Authorization-JSON-JWT)

- [Angular8 & Redux](https://github.com/soumyadip007/Angular-8-Redux)

- [Shopping-Cart-System-using-Angular-8-Auth-Module-Firebase (Mini Project)](https://github.com/soumyadip007/Shopping-Cart-System-using-Angular-8-Auth-Module-Firebase)

- [SpringBoot-Angular8-Login-Registration](https://github.com/soumyadip007/SpringBoot-Angular8-Login-Registration-for-JavaGuides.net)

# #Other Works

- [DBJ.jar (Framework for JDBC/On progress)](https://github.com/soumyadip007/DBJ.jar)

- [Ofline Route Builder & DTN (On progress)](https://github.com/soumyadip007/Offline-Route-Builder-DTN-Messenger-Android-GPS-OSM)

# #Wiki: https://github.com/soumyadip007/E-Medical-System-Web-Project-Using-Spring-Boot-Security-MVC-Hibernate-JPA-Rest-Thymeleaf-HQL/wiki
