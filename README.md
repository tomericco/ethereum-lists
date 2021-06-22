# ethereum-lists


A repository for maintaining lists of things like malicious URLs, fake token addresses, and so forth. We love lists.


this is a change




## Found a Phishing URL? See a fake ICO address?

Everyone is encouraged to make a PR or issue to add an address or URL to the list. This process is far easier than you might imagine!

1. If you do not already have a Github account, sign up. (it's free and easy!)

2. Navigate to the file you would like to make the adjustment to by clicking it's name.

3. Click the pencil icon in upper right.

4. If you would like to make an addition:

    - Copy the topmost item starting with the first ` { ` and ending with the ` }, `

    - Paste it right above the first item

    - Replace that information with the new information

    - Some add'l notes on specific files are below. Please skim if you don't know what the fields are.

5. If you would like to make a correction or remove an item:

    - Scroll to the item in question

    - Edit the item or remove the item by selecting the top ` { ` and ending with the ` }, ` and deleting that chunk.

    - Some add'l notes on specific files are below. Please skim if you don't know what the fields are.

6. Scroll to the bottom. under "Commit changes" enter a reason you are making this change.

    - Example: *"Adding myetherscam.com to darklist. See [link to tweet / reddit post / screenshot]."*

    - You can also provide more details in the box below. Please provide as much detail / evidence as reasonable so reviewers can verify quickly.

7. Click the green "Propose File change" button.

8. This next page is a review of what you did. Proofread and stuff.

9. Click the "Create Pull Request" button.....twice.

10. That's it. You successfully made a new pull request and helped make the world a better place! Tell all your friends.





## Address Darklist

`addresses-darklist.json`

-  **Purpose**: A list of addresses that deserve to be accompanied by a warning.
-  **Example**:
    -  Fake twitter handle ShiftShape is DMing telling people to send ETH to `0x1234...` for discount.
    -  VitalikBooty DMs you a link telling you to enter your private key in order to 2FA your wallet.
-  **Not for:**
    -  Tracking addresses of phishers or scammers.
    -  Reporting where stolen funds were sent to.



## Address Lightlist

`addresses-lightlist.json`

-  **Purpose**:
    -  A list of addresses that are the "legitimate" addresses.
    -  Optionally accompanied by a recommended gas price for sending to (for token contributions mostly)

-  **Example**:
    -  Upcoming token sale wants to ensure people sending to their address know to use a gas price of 200000.

*Best if you use github account that is part of token team or tweet or email us or something to verify. We should all get in the habit of cross-referencing provided information.*




## URL Darklist

`urls-darklist.json`

-  **Purpose**:
    -  A list of URLs known to be fake, malicious, phishing.
-  **Example**:
    -  `myetherphish[.]com`
-  **Not for:**
    -  Opinions on whether a project / token sale is a bad project.


## URL Lightlist

`urls-lightlist.json`

-  **Purpose**:
    -  A list URLs that are caught by the Levenshtein algorithm above or are known to be the "legitimate" URLs.
    -  Usually are added if a URL is added to the above.
-  **Example**:
    -  `myetherwallet.com`
-  **Not for:**
    -  Promoting your social media shit.





## ENS Darklist

*Not currently used for anything meaningful but figured it'll be needed eventually.*

`ens-darklist.json`

-  **Purpose**:
    -  A list of ENS names that deserve to be accompanied by a warning.



## ENS Lightlist

*Not currently used for anything meaningful but figured it'll be needed eventually.*

`ens-lightlist.json`





## Contract ABIs

ABIs associated with contract addresses. This should probably go away but meh.

-  `contract-abi-etc.json` (ETC chain)
-  `contract-abi-eth.json` (ETH chain)
-  `contract-abi-kov.json` (Kovan Testnet)
-  `contract-abi-rop.json` (Ropsten Testnet)
-  `contract-abi-rin.json` (Rinkeby Testnet)
-  `contract-abi-rsk.json` (Rootstock network)




## Tokens

Information related to tokens. ERC-20 compliant only, please.

TODO: compile down to a short version with just name, symbol, address, decimals.

-  `tokens-etc.json` (ETC chain)
-  `tokens-eth.json` (ETH chain)
-  `tokens-kov.json` (Kovan Testnet)
-  `tokens-rop.json` (Ropsten Testnet)
-  `tokens-rin.json` (Rinkeby Testnet)
-  `tokens-rsk.json` (Rootstock network)

##### Information (all optional except for name, symbol, address, decimals):

-  `symbol`:    Short ticker style symbol of token.
-  `name`:      Longer human version of token.
-  `address`:   Ethereum (or other chain) address of ERC-20 token.
-  `decimal`:   The decimals of the token.
-  `logo`:      An optional logo of your token. Must be a **square** (recommended: 128x128) PNG w/ transparent background. Please compress using https://tinypng.com/
-  `support`:   A support email, support URL, or other way people can get assistance regarding the token.
-  `github`:    Where token or project-related code lives.
-  `community`: Twitter, Reddit, Slack or wherever else people hang out.
-  `website`:   Official URL of the website.



#### Maintainers

- [409H](https://github.com/409H/) (EtherAddressLookup)

- [tayvano](https://github.com/tayvano/) (MyEtherWallet)

- You!




#### A last note

This list is maintained by volunteers in the cryptocurrency community &amp; people like you around the internet. It may not always be up to date, and it may occasionally get it wrong. If you find an error or omission, please open an issue or make a PR with any corrections.
