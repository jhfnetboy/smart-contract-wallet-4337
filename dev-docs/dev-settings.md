## Dev settings
+ env example
+ see file, more detail contact david.

### Git branch and Directory setting
+ 
### Gas analysis map
+ https://mm.edrawsoft.cn/app/editor/z7sI46yuwfvIpSVtTCMLX1KtVuF8KSjA? ivt=2AI6gPzk7sFyzCdKxBUQPsC5Web7EE25014?
You are invited to join the MindMaster collaborative version file "Pay on behalf of others" for collaboration.
+By the way, you can do it without using paymaster. If a user has a request to our server, we will directly bundle two transactions before sending it.
1. Transaction: Pledge user's contract wallet from our account.
2: The transaction of user's contract wallet is being executed.
Two transactions are in a userOperation array.
+If you don't use paymaster, the wallet generation is quite complicated. Calculate the contract wallet address offline, then you need an eoa address to deposit to the generated create2 address in entrypoint, and then construct the useroperation transaction and send it to entrypoint.

### Server offline signature tx
+ https://github.com/eth-infinitism/account-abstraction/blob/develop/contracts/samples/VerifyingPaymaster.sol

### Test addr
+I created a test network address and typed 20 test ETH.
Address:
0xeC9a6761a181C942906919Cc73C38de96C6FdFBD
Private key:
a6df89ed3e4f20e095f08730dd5435875ee6fa6e2b33bca5fb59f62afc06a56b

I found that debugging took more time, and many of them were due to the problems of my local test node [laughing through tears]
After debugging, you can directly test the chain. The above 20 ETH is enough to test all the tests in the chain. If you test, you don't need to apply for the test currency. Just use the above address. Haha, I also use the above address to test.

