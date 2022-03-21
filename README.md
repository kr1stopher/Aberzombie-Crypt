# Aberzombie-Crypt
Blockchain project for cryptoZombies DApp
Group Members:
- Kristopher Swartzbaugh, 890939184, kswartzb@csu.fullerton.edu
- Brian Tan, 897736286, brian388@csu.fullerton.edu
- Dano Nahabedian, 890245475, dnahabedian@csu.fullerton.edu
- Triet Phan, 888894532, trietphan@csu.fullerton.edu

Improvements made to the starter code:
1. Customized background
2. Stylized buttons. Changes color on hover.
3. Added 3 buttons: Attack Zombie, Feed on Kitty, Transfer Zombie
4. Text input field for desired zombie name
5. Able to create more than 1 zombie
6. Zombie details show who owns it according to Owner Account
7. Attack functionality works, but sporadically. Currently set to have Zombie 1 battle Zombie 2 only.
8. Connection to rinkeby testnet successful.

Notes:
- Feed on Kitty, Transfer Zombie functionalities are work in progress. 
- Upon successful attack operation, the winner does not multiply. But wins and losses counters update correctly.
-
- To connect to rinkeby test network:
  - I used infura to get an API key. Paste your API key in truffle-config.js line 52.
  - in truffle-config.js, comment out lines 45-49. 
  - Uncomment lines 50-55, and line 21, 25. 
  - This is to change the network to deploy to.
  - in command line, navigate to cryptozombie directory.
  - install hd wallet. npm install --save truffle-hdwallet-provider
  - then, truffle migrate -f 2 --network rinkeby
  - copy ZombieOwnership contract address, paste into index.html line 238.
  - run index.html, ensure metamask is connected, and with sufficient funds.



