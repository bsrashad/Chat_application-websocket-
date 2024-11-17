# Chat_application-websocket-
This is a real-time chat application built using Django Channels and WebSockets. It enables multiple users to communicate in real time within chat rooms. The application uses a in Memory Channel layer  to facilitate group communication, ensuring all participants in a chat room can send and receive messages instantly.
How It Works
- Users establish WebSocket connections to the server.
- Messages sent by users are processed by Django Channels consumers.
- Messages are broadcasted to all participants in the same chat room using the channel layer.
- The frontend dynamically updates the chat interface with new messages.
