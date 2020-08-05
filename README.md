## Apps deployed on heroku 
- https://zerouipinbot-api.herokuapp.com/
- https://zerouipinbot-peer.herokuapp.com

## checking the installed pinbot server to get multiaddr
- https://zerouipinbot-api.herokuapp.com/api/v0/peer

## multiaddr recieved 
"/dns4/zerouipinbot-peer.herokuapp.com/wss/p2p/QmR9PgePUo1ysniU6Q9H3SfEt2Thas5XErYyoKQfV5d7m3"

## using multiaddr in the ghost chat app
const box = await Box.openBox(myAddress, window.ethereum, { ghostPinbot: "/dns4/zerouipinbot-peer.herokuapp.com/wss/p2p/QmR9PgePUo1ysniU6Q9H3SfEt2Thas5XErYyoKQfV5d7m3" }) 
