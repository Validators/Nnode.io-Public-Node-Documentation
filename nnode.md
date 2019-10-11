Nnode.io - A cluster of blockchain nodes (public nodes)
=====================================
At Validators.com we received a grant from the [Web3 Foundation](https://web3.foundation) to build a cluster of polkadot nodes that would give easy and reliable access to the blockchain. Mostly Dapp developers will benefit from this as they can then focus their efforts on their core business - the dapp. 

The project was funded within four milestones:

Milestones
---------------

**Milestone 1:** This was the preliminary milestone and would function as a test setup. A couple of servers was initiated with Ubuntu installed. The Polkadot node/client was installed and run on each server. At this stage a proxy service called Cloudflare was used to setup a load balancer for each node with a simple round robin selection procedure.

**Milestone 2:** This includes the Developer Portal website that is now called https://nnode.io where users can register and get an API-Key for their dapp project. This gives them analytics of how much traffic is going through their dapp to the blockchain. And will also allow them to scale their operation beyong the free edition. To setup your own developer portal use this source code: https://github.com/Validators/Developer-Portal

In addition, a node monitor dashboard was created which source code can be found at: https://github.com/Validators/Polkadot-Node-Monitor. This will also be integrated into the nnode.io toolbox.

**Milestone 3:** To facilitate easy update of the blockchain nodes a couple of bash scripts was created. Can be found here: https://github.com/Validators/Polkadot-Infrastructure/tree/master/Scripts

**Milestone 4:** Final milestone that puts it all together at the https://nnode.io website. Examples of load-test of the clusted nodes can be found here: https://github.com/Validators/Polkadot-Infrastructure/tree/master/Loadtests

* * *

Feel free to goto https://nnode.io and use our free public blockchain nodes for Polkadot or Kusama.