

?> In this tutorial, we will guide you through the Golem Network Token migration process. We hope you find this process fairly simple and intuitive, and with this tutorial, you should be fully ready and feel more confident to migrate your GNT to GLM, the new token. Please take your time and make sure that you have read our [FAQs](https://blog.golemproject.net/gnt-to-erc20-migration-faqs/).

---

<iframe width="100%" height="315px" src="https://www.youtube.com/embed/DYX9Xn2HyWw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Safety first!

The first thing you want to do is **check the website address and the SECURITY CERTIFICATE (green padlock symbol next to the address)**. Please check this every time you visit the migration website just to avoid falling into scams such as duplicate sites. The address should say **migrate.golem.network**, and the certificate (green padlock symbol) should verify this.

![safety](/img/migration-tool-01.jpg)

---

### Ways to migrate to GLM

> **Sidenote:** We chose the Metamask for our migration application. You can easily import any Ethereum address into this wallet, and it supports multiple accounts. Most importantly, you can easily use [your hardware wallets](https://metamask.zendesk.com/hc/en-us/articles/360020394612-How-to-connect-a-Trezor-or-Ledger-Hardware-Wallet) with it. You will also be able to migrate with and [MyCrypto](/Products/Migrate/migration-guideline?id=external-wallet-support) once their widget is ready and [script](Products/Migrate/migration-guideline?id=migrating-via-automated-script) when we’ve concluded the mainnet test.


**There are three options for you to migrate your GNT to GLM with our [migration app](https://migrate.golem.network/):**

* [Migration from an Ethereum address](/Products/Migrate/migration-guideline?id=path-1-migration-from-an-ethereum-address)
* [Migration from the Golem app with an additional Ethereum account](/Products/Migrate/migration-guideline?id=path-2-migration-from-the-golem-app-with-an-additional-ethereum-account)
* [Importing your Golem keys to Metamask](/Products/Migrate/migration-guideline?id=path-3-importing-your-golem-keys-to-metamask)

The first two migration paths are pretty straightforward and intuitive. The third one, even though rather simple as well, has some limitations which should be considered before deciding to go forward. Please be advised, that if you want to continue using Clay Golem (that supports only old GNT) - you will need to create a new account, as the one you are migrating from will no longer be usable and compatible with Clay Golem token standard. 

---

## Path 1: Migration from an Ethereum address

To use Golem’s migration tool you will be asked to accept its terms and conditions. Without such permission we will not be able to support you in executing token migration.
After agreeing to terms and conditions, you should connect the migration tool with your Metamask account (2). 

![connect-to-metamask](/img/migration-tool-02.jpg)


The Metamask window will pop up. Please, make sure you are using the correct network (Ethereum Mainnet (3)) and that you are connecting to the right account (4). Now, confirm the connection between migration tool and Metamask (5).

![connect-to-metamask-confirm](/img/migration-tool-03.jpg)

This way you got the migration tool connected to your Metamask account.

![main-app-view](/img/migration-tool-04.jpg)

The information that will be presented after connection of the migration tool and your Metamask is your personal address, the amount of GLM (the new token) already at your disposal (when connecting for the first time the amount will be 0 as you have not proceeded with the migration yet), your balance of old GNT tokens and also ETH balance.
Please bear in mind that as we are using Ethereum, some ETH is needed to pay for transaction fees in the network. A small amount should be absolutely sufficient to execute your migration process. To check current gas prices visit [ETHgasstation](https://ethgasstation.info/). 

![confirm-in-app](/img/migration-tool-05.jpg)

Now, that you know what are the balances of your assets and the migration tool is effectively connected to your Metamask, you are ready to go through migration itself! 
- First, type in (11) your desired amount of tokens to migrate. If this is your first time performing a migration, we suggest doing the operation with a small amount to test if the migration process works properly without risking losing a large portion of your assets.
- After typing in the required amount, the tool will present you the amount of the new GLM tokens that you will receive (12) in exchange for the specified amount of old GNT tokens. 
- The exchange rate is 1:1. The tool will also check if you have the required amount of ETH to perform the transaction to the smart contract. 
- If you have the ETH and selected the amount of the old GNT, and are sure that the amount you typed in is correct, then click the Confirm transaction button (14).

![confirm-in-metamask](/img/migration-tool-06.jpg)

- The Metamask window will pop up again for you to confirm the transaction. In this step, you can also adjust the transaction fee (15) in order to make your transaction mine quicker or choose a more budget-friendly but slower approach to the execution of your migration process. To do so, just type in the required amount expressed in GWEI in the “gas price” window.
- After all the adjustments and amounts are correct, please confirm the transaction (16). Default values set by Metamask are optimal in most cases. However, if you are keen to adjust them manually, please make sure to include reasonable amounts. If you’re not sure what the current gas prices are then we recommend checking ethgasstation.com and input amounts based on the current network state.

![migration-in-progress](/img/migration-tool-07.jpg)

Depending on the chosen gas price you might have to wait a while for the transaction to be mined, but as soon as it is completed you will be presented with the modal confirming the successful completion of your transaction(18). 

Congratulations! You’ve managed to migrate your old GNT tokens successfully. The updated amount of GLM (19) will be reflected in your account balance.

![migration-success](/img/migration-tool-08.jpg)

---


## Path 2: Migration from the Golem app with an additional Ethereum account

In case you decide to migrate your tokens directly from the Golem app before you start, **please make sure to deactivate the Concent Service first, and unlock the deposited funds**. 

?> Please, be advised that for security reasons and to mitigate possible attacks, all deposits from the app are time-locked for 48h in a "pending withdrawal". So, if you chose that approach remember to take care of unlocking your deposited funds with enough time reserve before planned migration. After 48h since the deposit unlock order, you will be able to withdraw all funds from your main GNT account.

**Now, that you have all your funds unlocked and available, please open your Golem app:**

1. If you are using the Golem GUI then expand the wallet window and click the “Withdraw tokens” button (1).

2. In the withdrawal window, you can put the requested amount, either by adjusting the amount or type it by hand (4). It can reflect your overall balance or just part of it, depending on how much of the old GNT you would like to migrate.

3. The next step is to adjust the transaction fee of your withdrawal (5). Remember, that in order to do a withdrawal you will need some amount of ETH on the account you are making a transaction from (in this case the Golem App wallet).

4. Go to your Metamask app, and copy the Ethereum address that you are going to use to migrate the old GNT tokens (2). You Paste the address that you have copied from the Metamask in the “Sending to” field in the Golem App (6).

5. The final (7) step is to confirm the transaction. The summary window will pop up for you, to be able to double-check the address and the amount that you are sending.

6. For the next steps, [follow this link](/Products/Migrate/migration-guideline?id=option-1-migration-from-an-ethereum-address).

![migrate-golem-app](/img/migration-tool-09.jpg)


Return to the Golem App. 


![withdraw-the-tokens](/img/migration-tool-10.jpg)

---

## Path 3: Importing your Golem keys to Metamask

!> **Important:**  Please bear in mind that Clay Golem app only supports the old GNT. Should you choose to import your Golem app keys to Metamask, after the migration of your old GNT, if you decide to continue using Clay Golem you will be required to create a new account, as the one you’ve imported keys from will no longer be usable. 

One more thing you need to take into consideration when choosing this approach is the fact that the Golem app uses GNTb tokens (wrapped tokens used for batched transactions to decrease the cost of transaction fees). In order to execute your migration process, you will have to unwrap those tokens directly in the migration app before moving to the migration process itself.

Having this in mind we’d recommend to withdraw the old GNT tokens to the external address synchronized with the Metamask, as this conversion is being done by Golem automatically during the withdrawal (please see the Migration from the Golem app with an additional Ethereum account section above). 

If your choice of approach is still to import your Golem keys to Metamask, you should go to the Golem directory, where you can find a file called keystore.json. It contains your private key connected to this account, encrypted with the password you configured when running Golem for the first time.

Your wallet keys can be found in your app directory. The locations of the app directories for each supported OS can be found in the description below:


* **Windows:** %LOCALAPPDATA%\golem\golem\default\mainnet (or \rinkeby for testnet)

* **MacOS:** ~/Library/Application Support/golem/default/mainnet (or /rinkeby for testnet)

* **Linux:** ~/.local/share/golem/default/mainnet (or /rinkeby for testnet)


**Importing the account into Metamask can be done in a few simple steps:**

1. Click your account’s icon
2. Select “Import Account”
3. Change the “Select Type” option to “JSON File”
4. Click “Choose file” and point Metamask to the keystore.json file mentioned above
5. Enter your Golem password in the “Enter password” field.

**Done! Your account is imported into Metamask. The next steps of migration are [described here](/Products/Migrate/migration-guideline?id=path-1-migration-from-an-ethereum-address).**

---

## External wallet support

MyCrypto (supports Ledger and Trezor):

You will also have the option to migrate your tokens using [Mycrypto](https://mycrypto.com/account) once their widget is available - in this way you can connect a Trezor or Ledger hardware wallet to migrate. Head over to the [MyCrypto blog](https://medium.com/@mycrypto) and be on the lookout for an announcement on their upcoming Widget. If you don't see anything there then please wait for an announcement from their team. Note that the 19th of November is the start of migration and users can migrate at any point following.

## Migrating via Automated Script

This alternative for migration is not recommended for regular GNT users and holders. It should only be used by exchanges or other custodians with proper security protocols and engineering teams. Following this migration process without the proper experience will risk loss of tokens. If you are not confident that this migration alternative is for you then use the regular migration application.

**Requirements**

This script can be used to migrate tokens from the old GNT to GLM tokens. To run the script, you need to have Node.js 10 or newer installed.

**Usage**

Setup project
1. `git clone https://github.com/golemfactory/gnt-migration-script.git`
2. `cd gnt-migration-script`
3. `npm install` 

To run the script you will need to set two environment variables:
RPC_URL: HTTP URL to an ethereum node (e.g. infura)
PRIVATE_KEY: Private key of the account holding old GNT tokens
4. Running `RPC_URL="..." PRIVATE_KEY="..." npm run migrate` will send the migration transaction

**Development**

To run tests, simply `run npm test`

---

## GLM Migration exchange support

If you’re storing your **GNT** in any of the following exchanges, there is no action required. They have expressed interest in migrating tokens on their user’s behalf. You do not need to migrate the tokens by yourself, we would recommend that you give your exchange time to organize and wait for an announcement. Larger exchanges will likely take longer to organize so please be patient. This list is continuously updated, so we might add more exchanges later:

* Binance
* Bitfinex
* Bithumb
* Bittrex
* Coinbase
* Huobi
* Okex
* Poloniex
* Upbit

If you have any questions, we suggest you contact them directly as they might be better positioned to answer your doubts. You always have the option to migrate tokens yourself.