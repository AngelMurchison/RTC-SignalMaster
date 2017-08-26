### SignalMaster
 Essentially a signal listener that will connect two devices via peer-to-peer connection. Will be set up on a central server and exclusively make/remove P2P connections.
 Start with "npm start".

### WebRTC
 The environment that our chatrooms will exist in. The user will connect to this service, which will make a call to signalmaster, opening a connection to the central server, and then wait for anyone to try to connect to that. If that all goes well, a peer-to-peer connection will be established.
 Start with "npm run test-page"
