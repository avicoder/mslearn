---
    layout: post
    title: Introduction to blockchain on Azure 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/intro-to-blockchain/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/intro-to-blockchain.svg">
####  1. Suppose a refrigeration truck freezer fails during shipment to the ice cream shop. The ice cream in the shipment melts. The freezer is repaired and the ice cream refreezes before delivery. How would the ice cream shop know if the shipment is out of compliance?


<i class='far fa-square'></i> &nbsp;&nbsp;The shipment is out of compliance temporarily. However, when the freezer is repaired, the temperature returns to freezing. The last transaction from the IoT temperature sensor updates the temperature in the ledger. Therefore, the shipment appears to be in compliance.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Smart contract logic sets the shipment non-compliant when the temperature is too high. The ice cream shop can check if the shipment is out of compliance before accepting delivery.

<i class='far fa-square'></i> &nbsp;&nbsp;You need to audit the blockchain history to determine compliance. Once you investigate the blockchain history, you can mark the shipment as being out of compliance.
<br />
<br />
<br />

####  2. Why is blockchain immutable?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Blockchain uses hashes to tamper-proof the data in the blockchain. Validation would detect the invalid blocks. Bad blocks would be thrown out during consensus. Therefore, blockchain cannot be changed in a healthy blockchain network.

<i class='far fa-square'></i> &nbsp;&nbsp;Blockchain ledgers are read only for participants by default. Only processes with the granted permission can write data. Since ledgers are read only to participants, they are immutable.

<i class='far fa-square'></i> &nbsp;&nbsp;Immutability depends on how you configure the blockchain network. It can be configured to be read only or immutable. However, blockchain is fully configurable. You can configure nodes to allow administrators to make changes to transaction history. The changes are synchronized automatically.
<br />
<br />
<br />

####  3. How do smart contracts enable business workflows?


<i class='far fa-square'></i> &nbsp;&nbsp;Smart contracts use pre-defined business workflow logic for common business scenarios.

<i class='far fa-square'></i> &nbsp;&nbsp;Smart contracts are client applications you write that call the blockchain to execute transactions and change ledger state.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Smart contracts contain state and programmable logic. Transactions instantiate smart contracts and execute functions that change state. Therefore, smart contracts enable you to create a business workflow.
<br />
<br />
<br />
