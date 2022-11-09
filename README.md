# Social

A distributed, decentralized, fully (and actually) serverless social network.

## Features
* Chat, which uses browser-network/db in the following ways:
  * Every chat is a room
  * Each person keeps track of their own messages, including room ID
  * There's no point in these not being encrypted, so each message is encrypted
    and only openable by the other participants in the room, so each member needs
    to know who all is in the room
  * A member can delete their message because it's only recorded in their state
* Direct peer to peer video calling
* Up to a small number of photos, so it's social, but so it doesn't bog down everyone's bandwidth and storage
* No posts, this is more to facilitate communication and demonstrate browser network
* Every chat is also a chat room, so people can be brought in

## Factoids

* Data is saved on client computers only, there's literally no server at all. No hand rolled server, no firebase or other "serverless" (heavy quotes) concepts.
* Uses [Browser Network](https://github.com/browser-network) to facilitate this truly serverless architecture.
