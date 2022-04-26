# reactphp-thruway-websocket-chats

## Description
Example **ReactPHP** Project : **Websocket Chats**. With the help of **Thruway** PHP Client and Router Library for **Autobahn** (use authobahn-browser) and WAMP (Web Application Messaging Protocol) for Real-Time Application Messaging.

## Install
After clone and `cd` to this project. Install composer dependency
```bash
composer update
```

## Run
1. WebSocket Server
   ```bash
   php ws-router.php
   ```
2. Client
   
   Just visit `index.html` with your browser (I use Live Server from VS Code). Open `index.html` with multiple browser to see the realtime chat goes on.

   ![Result](docs/screenshot_1.png)