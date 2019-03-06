## Cross-Chain Transactions

Crosschain transactions are under this tab

![](_media/Wanwallet_crosschain.PNG)

Before you make a crosschain transaction, please check WAN and ETH balance in your account in Wanwallet GUI or with links below.

Main network：

* ETH: https://etherscan.io/

* WAN: https://www.wanscan.org/


Test network：

* ETH: https://rinkeby.etherscan.io/

* WAN: http://13.58.108.244/


### Send ETH to Wanchain

Click the "ETH >> WETH" tab below to send ETH to Wanchain

![](_media/Wanwallet_ETHtoWanchain.PNG)

Enter your password then press “OK” button to send the transaction.

![](_media/Wanwallet_sendTransaction.PNG)


#### Confirm/Cancel the transaction

In the "Transaction history" tab, click on the “**Confirm**" button to finalize the cross-chain transaction process once it _**turned red**_.

![](_media/Wanwallet_confirm_cancel_transaction.PNG)

If you do not confirm before the HTLC countdown ends, it means you choose to cancel the transaction and refund the ETH from the locked account. 
The "Confirm" button changes to "**Cancel**" and you can click it to cancel the transaction once it _**turned red**_



#### Option A) Confirm transaction

Once the “Confirm” button turned **red**, click it to access “**Confirm Transaction**” page.

![](_media/Wanwallet_confirm_transaction_1.PNG)

Enter the password then click “OK” button to finalize transaction 

![](_media/Wanwallet_confirm_transaction_2.PNG)



#### Option B) Cancel transaction

Once the “Cancel” button turned **red** (after countdown ends), click it to access “**Cancel Transaction**” page.

![](_media/Wanwallet_cancel_transaction_1.PNG)

Enter the password then click “OK” button to cancel the transaction 

![](_media/Wanwallet_cancel_transaction_2.PNG)


### Send WETH to Ethereum

If you have ETH balance on Wanchain (WETH balance), you can send WETH back to Ethereum.

Click the "WETH >> ETH" tab below to perform this kind of cross-chain transaction.    

![](_media/Wanwallet_WETHtoETH.PNG)

The process is similar to the ETH to Wanchain one, please refer to section 7 for details about how to confirm or cancel the transaction.

## Normal Ethereum transactions

You can also perform normal Ethereum transaction in Wanwallet GUI.

Click the "Normal transaction" tab below, fill source and destination accounts, transaction amount, fee preference, then click "SEND"

![](_media/Wanwallet_ETHtoETH.PNG)

## Private Transactions

>#### NOTE: Public & Private Addresses  
>Transactions made using public addresses are, as the name suggests, publicly visible. Transactions made using your private address (do not confuse with private key) on the other hand, are not be publicly visible.  
>**Public Address Example**  
>`0xefe000C1b9f9ca9bf063857aAF5fCb7B8A25eaA1`  
>**Private Address Example:**  
>`0x02bddd6c139a10c5c9e81d1d6438dd26bc4a26824a2c729819d21ee1fca8b2dbc203936c798596ac4adcbe89e96c88397894b6dfab14a95ea7e137c31f56b9c81255`  

### Sending Private Transactions

**Step 1**: Click the **Transfer** button on the right to start a private transaction


![](_media/Wanchain-Private-1.PNG)

**Step 2**: Click **Switch to Private** in the **From** field and enter a **Private address** in the **To** field. The Recipient will need to share their Private address beforehand. Enter the amount of WAN to send and click **SEND** to start the private transaction. 


![](_media/Wanchain-Private-2.PNG)

**Step 3**: Enter the **Password** for your account and click **SEND TRANSACTION** to send a private transaction. 

![](_media/Wanchain-Private-3.PNG)


**Step 4**: The latest transaction is displayed at the top of the **Transaction List**. 

![](_media/Wanchain-Private-4.PNG)

**Step 5**: On the **Wanchain Explorer**, the **Value**  and the **To** address are masked and hidden from the public.

![](_media/Wanchain-Private-5.PNG)


### Receiving Private Transactions

**Step 1**: Click **Details** to view detailed account settings

![](_media/Wanchain-Private-6.PNG)


**Step 2**: Click **Get OTA** to begin the process to receive a private transaction.

![](_media/Wanchain-Private-7.PNG)

**Step 3**: Enter the **Password** for your Account and Click **OK**. 

![](_media/Wanchain-Private-8.PNG)

**Step 4**: Wait a few minutes for the transaction to be processed and click **Redeem**. 

![](_media/Wanchain-Private-10.PNG)

**Step 5**: Click **Redeem** to accept the transaction.

![](_media/Wanchain-Private-11.PNG)

**Step 6**: The transaction details are show under **Redeem from OTAs**

![](_media/Wanchain-Private-12.PNG)