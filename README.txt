🟢 README – ZeroClassicChat v0.5

Version: v0.5
Author: Cityside
Date: October 2025

📘 Overview

ZeroClassicChat is a closed-source chat client that communicates directly through the ZeroClassic full node.
It uses the ZeroClassic peer-to-peer network with no central servers or third-party services.
As long as your full node is running, the chat can send coins and exchange messages across the network.

🔒 Verification (Recommended)

Verify your download to ensure file integrity.
Open Windows PowerShell in the same folder and run:

cd "C:\Users\YOURPCNAME\Desktop\ZeroClassicChat"
After that the follow command: Get-FileHash -Algorithm SHA256 ZeroClassicChat.exe

Open now ZeroClassicChat_v0.5.exe.hash as text,
And compare the displayed hash with the value inside

If they match, your file is mostly authentic original.
Always be carefull that you have download it from the right source!

⚙️ Installation Instructions

Install and start your ZeroClassic full node first. Make sure the node is fully synchronized and actively running. The chat will automatically connect to the locally running full node.

Download and extract the ZIP package. Example: ZeroClassicChat.zip

Extract it to a fixed location, e.g. C:\Users\YOURPCNAME\Desktop\ZeroClassicChat

First you need to start your Zero Classic Full node! https://github.com/zeroclassic/ZeroClassic/releases/tag/v4.4.4

The Zero Classic node must be configured correctly for the chat app to work. First find this file in map: C:\Users\YOURPCNAME\AppData\Roaming\ZeroClassic\zero.conf Make sure your zero.conf file includes the following essential settings:

zero.conf place lines in the file that show here under..
  
server=1
addressindex=1
experimentalfeatures=1
insightexplorer=1
listen=1
maxconnections=8
port=23801
rpcuser=YourRandomUsername       
rpcpassword=YourRandomPassword   
rpcport=8956  
rpcallowip=127.0.0.1
dnsseed=1

Start first your zeroclassic full node, it have to run as first. After that you start ZeroClassicChat.exe.
If you have problems to find peers, replace your peers.dat in the C:\Users\YOURPCNAME\AppData\Roaming\ZeroClassic\ folder.

The application will automatically connect to your local node. Once you synch up you can immediately send and receive messages.

⚠️ Windows Defender / Antivirus Warning

Why is Windows Defender blocking this file?
Since ZeroClassicChat is a new, unsigned application and not widely distributed yet, Windows Defender (and sometimes other antivirus tools) may flag it as suspicious by default.
This is known as a false positive and is common for independent or niche software without a verified publisher signature.

✅ What you can do:

If you downloaded from the official source, and the SHA-256 hash matches.
You may need to click “More info” → “Run anyway” when Windows Defender shows a warning.
You can also temporarily whitelist the file in your antivirus settings if needed.

🔐 Tip for safety:
Always verify the file's integrity with the included .hash file before running the app. See the Verification section above for details.

🧩 Files Included
File	Description
ZeroClassicChat.exe	        Main application (chat client).
ZeroClassicChat.exe.hash	SHA-256 checksum file for verification.
README.txt	                This manual.
LICENSE.txt	                Usage rights (closed-source).

🚀 Usage

Type a message in the main window and press Enter to send.
All messages are transmitted through the ZeroClassic network.
For additional info, see Help → About inside the application.

⚠️ Important Notes

All rights reserved.
This software is closed-source. Sending the Original upload or reupload is allowed, but reverse engineering, or modification is not permitted.

Works only with an active ZeroClassic full node:
https://github.com/zeroclassic/ZeroClassic/releases/tag/v4.4.4

💬 Support / Feedback

For questions or feedback, contact:
📧 Zero classic community on discord OR Discord: investeren_doe_ik_zo



