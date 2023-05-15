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


## Copyright @RAlain13
```shell
/**
 * 
 * @author Rushingabigwi Alain
 * @github RAlain13
 *
 */
```
## DB Diagram
![DBdiagram](https://github.com/RAlain13/23946HospitalMnagementSystem/assets/114587679/d7f1db0c-cb51-4c67-936e-de8a6a7da3d5)

