## Apps deployed on heroku 
- https://zerouipinbot-api.herokuapp.com/
- https://zerouipinbot-peer.herokuapp.com

## checking the installed pinbot server to get multiaddr
- https://zerouipinbot-api.herokuapp.com/api/v0/peer

## multiaddr recieved 
"/dns4/zerouipinbot-peer.herokuapp.com/wss/p2p/QmT668YWu2LxvwrZBU4cQuRqvWDLM9TcCG6gZx31WhRDzx"

## using multiaddr in the ghost chat app
const box = await Box.openBox(myAddress, window.ethereum, { ghostPinbot: "/dns4/zerouipinbot-peer.herokuapp.com/wss/p2p/QmXABkxnUaosVvvmXYmV24tbhCUFLLV2od9iiXcTkhwyQM" }) 
