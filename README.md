- Communicate with Slack API
- Go Channels (Think of them as Akka Actors)
- Go Channels are synchronous, they don't need to buffer messages, useful for orchestrating concurrency in a tighly controlled environment
- Type chan creates a channel, then transfers data of the same type
- Len, Cap, : 