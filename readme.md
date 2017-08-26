signalmaster - Essentially a signal listener that will connect two people on a peer-to-peer connection. Will exist on a central server and exclusively make/remove P2P connections.


webRTC - The environment that our chatrooms will exist in, the user will connect to this service, which will make a call to signalmaster, open a connection to the central server, and wait for anyone to try to connect to that. If that does happen, a peer-to-peer connection will be established.
