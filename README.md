# Alliance-Games-Worker-Node

# Why running an Alliance Games Worker Node
Alliance Games is a revolutionary Web3 gaming infrastructure provider,
offering a decentralized platform where blockchain-based games can thrive.
By contributing to its decentralized physical infrastructure network (DePin),
you can help host games in a way that reduces reliance on traditional, 
centralized servers. This guide will walk you through the process of farming 
Alliance Games nodes, allowing you to participate in the ecosystem, earn 
rewards, and contribute to a new era of community-owned gaming.
Alliance Games is backed by prominent industry players like Animoca Brands,
Spartan Group, and Overwolf, further solidifying its position as a leader in decentralized gaming infrastructure

Whether you’re an experienced gamer or someone interested in blockchain technology, setting up a node is your gateway to contributing to the future of decentralized gaming.

As usual DYOR about Alliance Games project :

Discord: https://discord.gg/alliancegames
Twitter (X): https://twitter.com/alliancegamesx
Website: https://alliancegames.xyz

`Before you continue reading, Alliance Games need an Alliance Pass that costs 9.9 USDT at the moment. If you can’t afford, you don’t need to read further.`

Alliance Pass
To run a worker node you need first to create an account and connect your wallet (I’m using Polygon Network with metamask as it’s easier to send funds on it).

To join you can use my referral link : [https://app.alliancegames.xyz](https://app.alliancegames.xyz/?referral=7VXXYY) or click on mint pass menu when you are on their site.

To mint a pass, it’s quite simple, ensure you have some matic for fees and 9.9 USDT on your wallet then click on Mint button.

![image](https://github.com/user-attachments/assets/7ad2c275-0f2a-4f90-8c00-4ab0e98db142)
Now let’s order a VPS, to run our nodes!

# Hardware Requirements:
VPS 1 Specifications:

CPU: 4 virtual cores
RAM: 6 GB
Storage: 400 GB SSD
Bandwidth: 32 TB outbound + Unlimited inbound (200 Mbit/s connection)
Price: Starting at around $6 per month
`Contabo VPS 1`

Register Alliance Games Worker Node
At this stage you should have minted your Alliance Pass.

On Alliance website, click on Worker menu to register a new worker then click on “Connect a worker”
![image](https://github.com/user-attachments/assets/f8e7fc53-a97d-45c2-8ea4-084652d8a8dd)

As we are about to farm multiple nodes, I rcommend using a Name pattern that is easy to remember and work with.

To register the worker, follow these steps :

Set a name, here i used NF0005 (because I’m NodeFarmer and this is my 5th node on Alliance Games) (this the pattern I decided to use, it’s up to you what you set here)
Select Linux Ubuntu (this guide is for Linux Ubuntu only)
Select Joins as Computing Node
Select AMD64 architecture (the script I will share to setup the node has not been tested on ARM64, so be sure you are running it on AMD64 server)
# Then click on “Next Step

![image](https://github.com/user-attachments/assets/15a6a861-16c6-44ad-92d5-d42d2c6daf23)
Here we will focus only on the third command block
Execute the below command to know your architecture.
```bash
dpkg --print-architecture
```


![image](https://github.com/user-attachments/assets/687f492d-4cdd-4485-8cad-8d7f0f7e6e5c)

`Don’t close this page or click back button, you need to stay with this page open to complete the setup process!`

ow we will connect on our VPS to setup the node

# Setup Alliance Games Node
To run the script :

Connect to Your VPS: Utilize an SSH client to access your Contabo VPS. For Windows users, [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) is recommended. If you are using mobile phone or Mac, I recommend using Termius. Use the root credentials provided by Contabo or the ones you set when ordering the VPS to connect.
Copy and paste the following commands in [terminal](https://termius.com/) (you can copy and paste all lines at once) then press ENTER


