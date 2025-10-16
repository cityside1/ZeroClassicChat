# ZeroClassicChat
A fully decentralized, public and private messaging app built on the Zero Classic blockchain. Encrypted communication owned and controlled by no one but you.

📘 <b>Overview</b>

ZeroClassicChat communicates directly through the ZeroClassic full node that runs all local on you computer.
It uses the ZeroClassic peer-to-peer blockchain network with no central servers or third-party services.
As long as your full node is running, the chat can send coins and exchange messages across the whole network.

<div style="display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">
  <img src="https://i.postimg.cc/KvxHxB0V/gitprevieuw.png" alt="git preview" style="max-width: 100%; height: auto; width: 45%;">
  <img src="https://i.postimg.cc/nc2wzrWS/gitprevieuw1.png" alt="git preview 1" style="max-width: 100%; height: auto; width: 45%;">
</div>

⚙️ <b>Installation Instructions</b>

Install and start your ZeroClassic full node first.
Make sure the node is fully synchronized and actively running.
The chat will automatically connect to the locally running full node.

Download and extract the ZIP package.
Example: ZeroClassicChat.zip

Extract it to a fixed location, e.g.
C:\Users\YOURPCNAME\Desktop\ZeroClassicChat

First you need to start your Zero Classic Full node!
https://github.com/zeroclassic/ZeroClassic/releases/tag/v4.4.4

The Zero Classic node must be configured correctly for the chat app to work.
First find this file in map: C:\Users\YOURPCNAME\AppData\Roaming\ZeroClassic\zero.conf
Make sure your zero.conf file includes the following essential settings:
<pre>zero.conf place lines in the file that show here under..
  
server=1
addressindex=1
experimentalfeatures=1
insightexplorer=1
listen=1
maxconnections=8
rpcuser=YourRandomUsername       # Make yourself a random username
rpcpassword=YourRandomPassword   # Make yourself a random password
rpcport=8956  # Default RPC port for your node
</pre>
<b>Start first your zeroclassic full node, it have to run as first.
After that you start ZeroClassicChat.exe.</b>

The application will automatically connect to your local node. 
Once you synch up you can immediately send and receive messages.

⚠️ <b>Important Notes</b>

All rights reserved.
This software is closed-source. Sending the Original upload or reupload is allowed, but reverse engineering, or modification is not permitted.

Works only with an active ZeroClassic full node:
https://github.com/zeroclassic/ZeroClassic/releases/tag/v4.4.4

💬 <b>Support / Feedback</b>

For questions or feedback, contact:
📧 Zero classic community on discord OR Discord: investeren_doe_ik_zo
