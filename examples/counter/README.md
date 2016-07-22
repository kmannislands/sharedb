# Simple client/server sync with ShareDB

![Demo](demo.gif)

This is a simple websocket server that exposes the ShareDB protocol,
with a client showing an incrementing number that is sychronized
across all open browser tabs.

In this demo, data is not persisted. To persiste data, run a Mongo
server and initialize ShareDB with the
[ShareDBMongo](https://github.com/share/sharedb-mongo) database adapter.

## Build client JavaScript file
```
npm run build
```

## Run server
```
npm install
npm start
```

## Run app in browser
Load [http://localhost:8080](http://localhost:8080)

