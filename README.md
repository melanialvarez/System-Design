# System Design

## Update UI
There are three approaches for this.
`Long Polling`: Send a request to a server every X interval.
`Web Sockets`: Real time connection. Double sided connection. (Like live chat uses)
`SSE`: Server Sent Events. Observer-Subscriber technique. Subscribe to events in the server. It sends updates in a binary format. It has longer latency than Web Sockets.

## Improve performance
### JS
1. Cache
2. Use web workers to perform async operations (As JS is single threaded)


## Strategies for a good UX

1. Show placeholders
2. PWA mode
	* Cache data to load content offline (Via service workers)
