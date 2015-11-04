
Trivicall: http://blog.vline.com/post/52644825765/tunneling-webrtc-over-tcp-and-why-it-matters
Upload progress bar

Todo
----------

* coding: WebStorm IDE; useCoffeeScript and SASS (while we're trying new things anyway)
  - coffee and node: http://stackoverflow.com/questions/4679782/can-i-use-coffeescript-instead-of-js-for-node-js
* server-side: node.js - http://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js
* client-side: peer.js - http://peerjs.com/ & bootstrap
* SSL: https://www.startssl.com/?app=1
* people can start rooms which are accessible by URL (like etherpad), which can have a maximum history time
* websites can embed the chat functionality in one of two ways
  - simply create an iframe with the chat - username can be passed through URL but is not protected, and the room is generally accessible
  - create a namespace with a (secret) key; rooms in that namespace need authentication, provided by URL /namespace/room?user=name&key=K3Y, where K3Y is hash of current hour, username, room and key
  - (there is another iframe which shows stats like new messages)


Misc
----------
* cooking for one session --> ??
* secure connection --> automatic
* do bootstrap fonts work?
* http://blog.vline.com/post/52644825765/tunneling-webrtc-over-tcp-and-why-it-matters
* 

