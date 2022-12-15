#Ethereum


Connect to Ethereum Test Node with Web3 Python on Colaboratory. 


A "node" is any instance of Ethereum client software that is connected to other computers also running Ethereum software, forming a network. A client is an implementation of Ethereum that verifies data against the protocol rules and keeps the network secure.

Post-Merge Ethereum consists of two parts: the execution layer and the consensus layer. Both layers are run by different client software. On this page, we'll refer to them as the execution client and consensus client.

The execution client (also known as the Execution Engine, EL client or formerly the Eth1 client) listens to new transactions broadcasted in the network, executes them in EVM, and holds the latest state and database of all current Ethereum data.
The consensus client (also known as the Beacon Node, CL client or formerly the Eth2 client) implements the proof-of-stake consensus algorithm, which enables the network to achieve agreement based on validated data from the execution client.
Before The Merge, consensus and execution layer were separate networks, with all transactions and user activity on the Ethereum happening at what is now the execution layer. One client software provided both execution environment and consensus verification of blocks produced by miners. The consensus layer, the Beacon Chain, has been running separately since December 2020. It introduced proof-of-stake and coordinated the network of validators based on data from the Ethereum network.

With the Merge, Ethereum transitions to proof-of-stake by connecting these networks. Execution and consensus clients work together to verify Ethereum's state.

Modular design with various software pieces working together is called encapsulated complexity. This approach makes it easier to execute The Merge seamlessly and enables the reuse of individual clients, for example, in the layer 2 ecosystem.

![image](https://user-images.githubusercontent.com/28503366/206746566-5095bfa7-80a9-4892-92f5-3fe4a33a04c9.png)


WHY SHOULD I RUN AN ETHEREUM NODE?

Running a node allows you to directly, trustlessly and privately use Ethereum while supporting the network by keeping it more robust and decentralized.
