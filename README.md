3 easy one-time steps and you're set for life ⛱️

# Step 1: Allow the contract to pet your gotchis
(This step is not required if you already used petting from gotchi world)
1. Head to https://www.gotchi.world/petting and click "approve interaction"

    ![image](https://user-images.githubusercontent.com/82118439/210274928-82410477-2ed8-4871-8007-69d18dfaab72.png)

# Step 2: Swap some Link
(You will need 5 Link token for this)
1. Head to https://pegswap.chain.link/: swap 5 ERC20 Link to ERC667 Link (1:1 ratio)
    You will have 2 transactions, 1 to allow spending your Link then one to swap them at 1:1 ratio
    ![image](https://user-images.githubusercontent.com/82118439/210274951-612f3b42-7fcb-4d7f-ad8c-ded979504dde.png)

# Step 3: Register your automation
1. ⚠️ Wait for the petting to be ready before registering (Status of all gotchis should be "Pet Me Master!")
2. Head to https://automation.chain.link/polygon/new
3. Select “Custom logic”
4. Use this contract address: 0x95De7026dEB42A7F13dFbb876999B28336f43270
    ![image](https://user-images.githubusercontent.com/82118439/210361346-3da36648-4546-4d9b-9994-8dfd6569834d.png)
5. Create the upkeep with 100 000 Gas per gotchis, up to 5 000 000 Gas max if you're over 100 Gotchis
6. Enter your token id in the check data adding 0x before and using 6 digit. For example, if you own token id 9321 enter 0x009321

    To find your Token ID go to https://www.fakegotchis.com/ then to your user profile, open the aavegotchi
    
    ID is on the link
    
    ![image](https://user-images.githubusercontent.com/82118439/210253612-8089274e-43e3-40df-bbb2-14e48c601c43.png)
7. Provide your email address to receive notification from chainlink about this automation (e.g you're running out of gas fund)
    ![image](https://user-images.githubusercontent.com/82118439/210273964-4bbfd2c0-5013-454a-8c52-d89d7ce4bccb.png)
8. Watch the magic operate
    
    ![image](https://user-images.githubusercontent.com/82118439/210330525-9849e586-8741-4fc8-aed6-e5465920d425.png)


# FAQ

- Does it pet lent gotchis?
    - Yes, this automation pet all the gotchis in your wallet (including borrowed gotchis) and the gotchis you lent.
- How many gotchis can this automation handle?
    - This automation should handle up to a 200 Gotchis but the exact amount can't be guaranteed. It can be higher in the future depending on chainlink.
    - You can’t increase this amount by having 2 FakeGotchis.
- How is the gas paid?
    - You pay for the transaction costs through chainlink’s automation tool.
    - Chainlink adds a premium on the transaction cost.
- If I sell the Fake Gotchi, does it stop my automation?
    - No, you need to go back to your upkeep in chainlink's site to stop it and take back your funds.
- If I get a new gotchi, when will it be pet?
    - The automation pet every 12 hours, so the new gotchi will be synced with the one actually being pet.
- Why use Chainlink and not another competitor?
    - I want this automation to last as long as possible, I believe Chainlink to be the highest quality product available.
- What if I run into an issue or have questions not in the FAQ?
    - DM ".ceza" on Discord.
- Will it work with Gotchichain?
    - At this point it's too early to know. The main issue is that chainlink probably won't be available on the Gotchichain.
    - This NFT is meant to be on Polygon only.
