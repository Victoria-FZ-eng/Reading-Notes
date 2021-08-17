# Spring and Sockets

This is a tutorial of how we develop a STOMP-based messaging service with Spring;build a server that accepts a message that carries a user’s name (using queues).

* Add web socket to the dependencies and others , check the reference provided.
* Create a Message-handling Controller; **@MessageMapping - @SendTo** annotations.
* Configure Spring for STOMP messaging ; **class WebSocketConfig implements WebSocketMessageBrokerConfigurer**.
* Create a Browser Client ; importing **SockJS and STOMP** javascript libraries.
* Make the Application Executable ; using **MessagingStompWebsocketApplication** class.
* Build an executable JAR


Reference:
* [Real time messaging with websockets](https://spring.io/guides/gs/messaging-stomp-websocket/)