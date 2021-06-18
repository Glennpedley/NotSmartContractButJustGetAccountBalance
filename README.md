# NotSmartContractButJustGetAccountBalance
This is supposedly Smart Contract but actually end up more javascript to get balances of account on the blockchain net thingy

So, what I do? I go search everywhere like dog and try here and there.
In the end, just copy and paste here.

The files here.<br>
1) web3.min.js is the web3 files.<br>
2) html file is put the two buttons, one for eth main address balance and one more for the token whereby we use the token's contract address.<br>
  html file also links to the other js files.<br>
3) TokenBalance.js file is the one running the requests.<br>
4) TokenABI.js file is the one where the variable TokenABI is stored.... it is like a code that will run to check the token's contract to see whether the main types of JSON variables are in the Token's contract and then to use these variables for certain functions. Like for get balance function, will need to send certain JSON objects, then this file is the one that looks for it(them). If transfer tokens, need other types of variables, again, this TokenABI file looks for it(them)<br>
