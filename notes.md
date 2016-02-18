
#### HTTP Methods
* GET
* POST
* HEAD
* OPTIONS
* PUT
* DELETE
* 

#### HTTP Status Codes
* 1xx (Informational)
* 2xx (Successful)
  * 200 - OK 
* 3xx (Redirection)
* 4xx (Client Error)
  * 403 - Forbidden
  * 404 - Not found
* 5xx (Server Error)
  * 503 - Service Unavailable 

#### Web application structure


#### Deploying descriptor

#### Servlet
* Servlet - basic interface
* GenericServlet - protocol independent implementation
* HttpServlet - http implementation
 
##### ServletContext

##### ServletConfig

##### Request Dispatcher  


```
RequestDispatcher requestDispatcher =
    request.getRequestDispatcher("/anotherURL.simple");

requestDispatcher.forward(request, response);

requestDispatcher.include(request, response);
```

##### Servlet Request/Response Wrapper
Request:
* ServletRequestWrapper
* HttpServletRequestWrapper

Response:
* ServletResponseWrapper
* HttpServletResponseWrapper

#### Servlet Listeners
* ServletContextAttributeListener
* HttpSessionListener
* ServletRequestListener
* ServletRequestAttributeListener
* HttpSessionBindingListener
* HttpSessionAttributeListener
* ServletContextListener
* HttpSessionActivationListener

####


#### Http Session






