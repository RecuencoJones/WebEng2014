# Hello World!
This project contains a demonstration of a the autentication infrastructure provided by [HttpServlet](http://docs.oracle.com/javaee/6/api/javax/servlet/http/HttpServlet.html). Note that this approximation enforces the client to authenticate by providing autentication credentials, however, it is impossible to enforce the client to do not continue sending autentication credentials. Therefore, applications should track if a client has performed an action that can be understood as a logout. An example of this approach can be found in [Hello Session!](https://github.com/UNIZAR-30246-WebEngineering/WebEng2014/tree/master/servlets/helloSession)

Deploy your code to a [Jetty](http://www.eclipse.org/jetty/) server with ```gradle jettyEclipseRun```. Then, open the page at [http://localhost:8080/](http://localhost:8080/).