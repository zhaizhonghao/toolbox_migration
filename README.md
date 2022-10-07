# A Toolbox for Migrating the Blockchain-based Application from Ethereum to Hyperledger Fabric

It is a toolbox designed for developers who want to migrate the blockchain-based applications from the Ethereum public blockchain to the permissioned blockchain built by Hyperledger Fabric.

The low transaction capacity (i.e., 15 transaction per second (TPS)), high transaction cost, and long-term privacy concerns of the current Ethereum are forcing developers to seek alternative blockchain platforms to migrate their application in order to reduce their applications' use-cost and improve their applications' user experience.

Hyperledger Fabric (HLF) platform introduces a new modular and extensible blockchain architecture with resiliency, flexibility, scalability, and confidentiality. It allows developers to flexibly select appropriate components, such as consensus protocols and membership services, according to their specific requirements. Compared to the Ethereum platform, developers can use the HLF platform to build blockchain-based applications with higher transaction capacity, lower use-cost, and better  privacy protection capabilities.

Hence, we designed a toolbox to help developers automatically migrate their applications from Ethereum to HLF. Specially, the toolbox provides following functions to ease the migration process

- Account Migration

  Ethereum is a public blockchain. The user can use almost all blockchain-based applications on the Ethereum platform as long as he/she generates a pair of public/private keys using the wallet (e.g., MetaMask).  On the contray, the blockchain built by HLF is a permissioned blockchain where the user has to obtain a valid and authorized identity in the permissioned network. Hence, The public key generated by the user’s Ethereum wallet will be not recognized after the application migration.  To solve the problem, the toolbox provides the account migration to enable users to continue to use their identities.

- Interaction Transformation

  

- Smart Contract Migration

- Binding Mechanism


