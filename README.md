### grpc-101

Based on: https://github.com/dwdraju/grpc-101

See: https://medium.com/@dwdraju/grpc-101-with-docker-nodejs-and-express-4c84ed00e88f

#### update
synced dwdraju's [example repo](https://github.com/dwdraju/grpc-101) with the [Medium](https://medium.com/@dwdraju/grpc-101-with-docker-nodejs-and-express-4c84ed00e88f) article
- added web server example
- added express dependency

#### run
Get the services running:  
```
$ docker-compose up -d
```
Check the logs  
```
$ docker-compose logs -f
```
Finally, send request to client  
```
$ curl localhost:3000/raju
```

In the logs, see the response  
```
Attaching to grpc-client, grpc-server
grpc-client    
 Example app listening on port 3000!
grpc-client    
 Greeting: Hello raju
 ```