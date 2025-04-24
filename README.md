# Ghaymah-WebRTC-Demo
### 1. Open Peer 1 (Initiator)
#### Run its code in your first browser tab

### 2. Copy Offer to Peer 2
#### Check browser console for the final SDP offer

#### Copy the complete localDescription object

### 3. Open Peer 2 (Responder)
#### Run its code in a second browser tab, pasting the offer

### 4. Copy Answer to Peer 1
#### Copy the final SDP answer from Peer 2's console
#### Back in Peer 1's tab, complete the connection:

### Sending Messages

From Peer 1:
sendChannel.send("Hello from Tab 1!");

From Peer 2:
peer2Channel.send("Hello back from Tab 2!");
