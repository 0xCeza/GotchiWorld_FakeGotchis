# Step 1: Allow the contract to pet your gotchis
(This step is not required if you already used petting from gotchi world)
1. Head to https://www.gotchi.world/petting and click "approve interaction"

# Step 2: Swap some Link
(You will need 5 Link token for this)
1. Head to [https://pegswap.chain.link/](https://pegswap.chain.link/) : swap 5 ERC20 Link to ERC667 Link   ⇒ 2 tx (Allow + Swap)
    1. You will need 5 Link to start.

# Step 3: Register your automation

1. ⚠️ Wait for the petting to be ready before registering
2. Head to [https://automation.chain.link/polygon/new](https://automation.chain.link/polygon/new)
3. Check “Custom logic”
4. Paste this contract address : 
5. Create the upkeep with 5 000 000 Gas 
6. Provide your email address to receive notification from chainlink about this upkeep
7. Enter your token id in the check data as follow adding 0x before. If your token id using 6 numbers, so id 9321 is 0x009321
    1. To find your Token ID go to [auction.aavegotchi.com](http://auction.aavegotchi.com) to your user profile, open the aavegotchi. ID is on the link

# FAQ

- Does it pet lent gotchis?
    - Yes, this automation pet all the gotchis in your wallet (including borrowed gotchis) and the gotchis you lent.
- How many gotchis can this automation handle?
    - This automation should handle up to a 200 Gotchis but it can’t be guarenteed.
    - You can’t increase this by having 2 FakeGotchis
- How is the gas paid?
    - You pay for the transaction costs through chainlink’s automation tool.
    - Chainlink adds a premium on the transaction cost.
