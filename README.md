# Spring
Spring founder Rod Johnson

### Versions

version |	date
--------|-----
0.9     |	2002
1.0     |	2003
2.0     |	2006
3.0     |	2009
4.0     |	2013
5.0     |	2017

### Goals
1. lightweight development with java POJO.
2. dependency injection
3. declarative programming with AOP.
4. minimize boilerplate java code.

### Inversion of Control

* **IoC**: the approach of outsourcing the construction and management of objects.

* **Bean**: java object managed by Spring IoC container.

* example: look papers

### Dependency Injection

* **DI**: the client delegates to calls another object the responsibility of providing its dependencies.

* example: look papers

* types:
  * constructor injection
  * setter injection
  * method injection
  * inject literal values
  * inject values from property file

### Bean Scope
https://docs.spring.io/spring-framework/docs/3.0.0.M3/reference/html/ch04s04.html?

scope          | type      | description
---------------|-----------|-----------------------------------------------------------------
singleton      | stateless | create a single shared instance of the bean. (**Default Scope**)
prototype      | stateful  | create a new bean instance for each container request.
request        |           | scoped to an HTTP web request, only used for web apps.
session        |           | scoped to an HTTP web session, only used for web apps.
global-session |           | scoped to a global HTTP web session, only used for web apps.

### Spring MVC
Framework for building web applications in java based on  Model-View-Control design pattern.
![](https://github.com/shamy1st/spring/blob/main/spring-mvc.png)


















