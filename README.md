# Gateway

This repository contains the source code for the __Gateway Server__. The Gateway Server acts as the central access point for the streaming platform, handling API requests, managing authentication, and routing traffic to the appropriate services, such as the __Streaming Server(PDN-WebRTC)__ and the __Admin Dashboard Server__.

## Features

- __API Routing__: Directs API requests to the appropriate services, such as the Streaming Server for video and chat functionalities and the Admin Dashboard Server for management tasks.
- __Authentication and Authorization__: Verifies API keys and JWT tokens to ensure secure access to services.
- __Traffic Control and Rate Limiting__: Manages traffic flow, prevents abuse, and ensures fair use by implementing rate limiting.
- __Load Balancing__: Balances requests across multiple instances of backend services for improved reliability and scalability.
