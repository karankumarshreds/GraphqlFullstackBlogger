#### SERVER 

> npm install apollo-server graphql



#### Important points: 

In graphql we always make POST requests

The request payload contains
```javascript 
{
    "operationName": null,
    "variables": {},
    "query": {query_name}
}
```
The response from graphql returns a json object in return.