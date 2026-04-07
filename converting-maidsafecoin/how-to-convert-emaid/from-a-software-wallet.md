---
description: >-
  How to convert from eMAID to Autonomi tokens if your coins are on a software
  wallet, such as MetaMask.
---

# From a Software Wallet

{% stepper %}
{% step %}
## **Burn Your eMAID Tokens**

* Go to the [eMAID contract address on Etherscan](https://etherscan.io/address/0x329c6e459ffa7475718838145e5e85802db2a303)
* Click on **Contract**, then select **Write as Proxy**.

<figure><img src="../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

* Connect your ETH wallet holding eMAID using **Connect to Web3**.

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

* In the burn dropdown, enter the number of tokens to burn and confirm the transaction.

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**Note the format here is `uint256`**. You should write the amount of eMAID you wish to burn as an integer with 18 decimals. That means 18 trailing zeros.\
\
For example `1`eMAID is written as `1000000000000000000`
{% endhint %}


{% endstep %}

{% step %}
### **Wait for Verification**

No further action is required. The system will automatically detect your burn transaction.&#x20;
{% endstep %}

{% step %}
### **Receive your** Autonomi tokens

Your Autonomi tokens will be airdropped to the same ETH wallet from which you burned your eMAID. The number of tokens received will match the number of burned tokens 1:1. Please be patient, as this is on a [set schedule](../timeline.md).&#x20;
{% endstep %}
{% endstepper %}

{% include "../../.gitbook/includes/in-order-to-see-the-tokens-....md" %}
