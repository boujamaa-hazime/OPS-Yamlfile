- ### What is YAML?
YAML is a data <mark style="background: #ADCCFFA6;">serialization</mark>  language like XML and JSON.
serialization: standard format to tranfer data

-----------------------------------------------
###             File extentions:       <mark style="background: #CACFD9A6;">.yaml</mark>        or                  .<mark style="background: #CACFD9A6;">yml</mark>

------------------------------------------------------------------------------------------------------------------------------------------
ex: yaml
```yml
microservices:
- app: user-authentication
port: 9000
version: 1.0
```
ex: json
```json
{
microservices: [
app: "user-authentication",
port: 9000,
version: "1.0"
}
```

for yaml:  we need to have a line <mark style="background: #D2B3FFA6;">separation</mark> and <mark style="background: #D2B3FFA6;">indentation</mark>

-----------------------------------------------------------------------
------------------------------------------------------------------------
#                      Basic Syntax of YAML 
-----------------------------------------------------------------------
-----------------------------------------------------------------------
### key-value paire    
### comments 
### objects
```yaml
#comant here also this is an object 
 microservice:
  app: user-authentication
  port: 9000
  version: 1.7 
```


 *u can fin a web site that test your yaml syntax*

- we can have lists :
```yaml
#comant here also this is an object 
 microservice:
  -app: user-authentication
   port: 9000
   version: 1.7 
```
- we can have boolians :
```yaml
#comant here also this is an object 
 microservice:
  -app: user-authentication
   port: 9000
   version: 1.7 
   deployed: yes or on off 
#list of objects
  -app:shopping-cart
   port: 9002
   version: 1.7 
   deployed: yes or on off
```

```yaml
microservices:
 - app: user-authentication
   port: 9000
   version: 1.7
 - app: shopping-cart
   port: 9002
#u can right it like this too 
#  versions:[1.9, 2.0, 2.1]
   versions:
   - 1.9
   - 2.0
   - 2.1
microservices:
 - user-authentication
 - shopping-cart
```
---------------------------------------------------------
-----------------------
```time
8:48    to be continue
```
Yes work hard boss!