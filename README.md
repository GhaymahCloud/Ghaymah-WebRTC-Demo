# Ghaymah-WebRTC-Demo
## 🌐 Core Concepts

```mermaid
graph TD
    A[Peer 1] -->|1. Create Offer| B[Copy SDP]
    B -->|2. Paste in Peer 2| C[Peer 2]
    C -->|3. Create Answer| D[Copy SDP]
    D -->|4. Paste in Peer 1| A
    A -->|5. Data Channel| C
