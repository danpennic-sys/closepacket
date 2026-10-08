# ClosePacket

Local job-closeout for trades. One HTML file. Customer signs on the device. Photo and file bytes are hashed with SHA-256 in the browser and never uploaded. Print the packet or download the evidence JSON.

Sits after Operator Desk (quote and invoice) and before Chaser (balance follow-up). The JSON is a manifest QuantumGuard can be pointed at later. This file does not sign with Ed25519.

Open `index.html` in a browser. Data stays in `localStorage` under `closepacket.v1`.

Operator Pages · danpennic@gmail.com
