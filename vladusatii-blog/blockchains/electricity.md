# Electricity: A primer

**By Vlad Usatii**

Anybody who has ever used a cryptocurrency to make a transaction notices at one point or another the extremely expensive fee paid to the creators of the blocks in turn of guaranteeing a secure and fast addition of a transaction function to the chain of digital signatures. In this process, cryptocurrencies re-use their digital dollars or update state and don't have to mint as many coins in regards to a mining reward.

But the social cost of having an expensive operation and storing valuable data on valuable disk space seems to be "worth the splurge" (many people disagree with this half-intuitive, half-speculative statement). A large group of individuals are starting to move away from the trend of gas, signalling a problem with the high-latency peer-to-peer consensus mechanisms and the overpriced cost of generating transactions in append-form to blocks. And with the democratization of mining (memory-hard algorithms like Dagger), we may need more democratization and removal of obstacles that block the path of the general public in their road to making a simple transaction and advancing their socio-economic status. The speed of the chain (optimization) and the gas fee (taxing to reward a miner) are two high-latency, code-dense, mathematically-complex systems that must find better solutions to grow the crypto economy we see today.

So, to make it more clear, many people don't think that $15 (in conversion) or something similar is an equal social cost to the reality of a miner's situation. Participants in the network don't think that sending 0.00004 GEM should cost 0.004 GEM. The entire network is plagued with a fee, while the miner who invested his/her life savings benefits and increases a divide between the participant nodes and the miner nodes.

It is for the reasons stated above, and in sequential order too, that I came along and designed both a "gas fee" and an alternative "credit/proof-of-gas fee" to go along with it.

And it is with that gilded introduction that I introduce you to my fragmented and confusing technology: Electricity. Not that kind of electricity -- we're talking about a replacement (or addition -- it depends on how you look at it) for gas fees on the modern blockchain.

Before we can step into the complexity of the architecture behind Electricity, I'll make it known that you should have a solid understanding of calculus, zk-SNARKS, and what Proof of Work is, along with what a gas fee does and how it is measured.

Let's break this apart.

### Step 1: Measuring a Transaction's Size

Many methods attempt at 
