This example shows how to use Axis2 in a servlet container.  
\# modify demo code from [How to Embed an Axis2 based Web Service in your Webapp?](http://wso2.org/library/90)

Run Server
==================

```bash
mvn install

# Run Web on port 8080
mvn jetty:run
```

Run Client
=================

Access In Browser
----------------

```bash
# Show WSDL
http://localhost:8080/services/BookService?wsdl

# Invoke Service
http://localhost:8080/services/BookService/getBooks
http://localhost:8080/services/BookService/findBook?isbn=0123456789
```
