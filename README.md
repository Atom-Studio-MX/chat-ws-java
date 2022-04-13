[![Build Status](https://travis-ci.org/jasofalcon/chat-ws-java.svg?branch=master)](https://travis-ci.org/jasofalcon/chat-ws-java)

# chat-ws-java
Simple web socket chat server in Java, using WebSockets 

# Demo
Server is already running on Heroku, you can check the client by visiting https://jasofalcon.github.io/chat-ws-client/

## Compile

```bash
mvn clean package
```

## Run
Just fire up the ChatServer.java (::main) 

```bash
java -jar target/chat-1.0-SNAPSHOT-jar-with-dependencies.jar
```
## Run the client
Use this client to connect with server - https://github.com/jasofalcon/chat-ws-client
