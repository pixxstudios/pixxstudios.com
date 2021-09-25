---
title: "WebSockets"
author: "Gagandeep Singh"
date: "2021-09-17"
categories: 
  - "javascript"
tags: 
  - "websockets"
  - "javascript"
draft: true
---

WebSockets allows a two way persistent connection between client and server. So rather than client having to poll (call the endpoint and fetch new data) the backend, server sends the response by itself if there is updated data available. Also since it's a two way connection, client can send messages to server as well.

- open – connection established
- message – data received
- error – websocket error
- close – connection closed
