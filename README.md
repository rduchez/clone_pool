# clone_pool
AS3 template to be used for creating a clone pool associated to a virtual server.   
In this example, the VS IP address is 0.0.0.0/0 (all ip addresses).  
The pool member for the application is 10.0.253.131.  
The clone pool listens on 10.0.253.350.

These can be parametricized if using ansible or other automation tool. 
