# Introduction
These basic application are all my solutions, ideas and experiences put together in one boilerplate application to be used as a base for new node/express/pug implementations.

# Features
- asynchronous startup routines
- graceful, asynchronous shutdown:
  - waiting for all http clients to disconnect
  - "Connection: close" header send during shutdown
  - customizable timeout
- customizable logging level
- verbose debug logs
- error handling
- .env, .env.defaults support for all application settings
- requests processing times tracked
- http clients connecting/disconnecting tracked
- tcp connections times and bytes sent/received tracked
- webserver timeouts set explicitly
- no etag and x-powered-by http response headers
- static assets urls versioning
- optional access log
