### Overview

SeraphID-SelfSovereign is a cutting-edge self-sovereign identity (SSI) solution developed on the EpicChain blockchain platform. This innovative technology is designed to give individuals full autonomy and control over their personal identity data, fostering a decentralized and secure approach to identity management. By eliminating the need for central authorities or intermediaries, SeraphID ensures that users have complete ownership and management of their personal information. This solution is implemented using **did:epic** identifiers, facilitating a streamlined and secure method for identity verification and management.

### Example DIDs

Here is an example of a **did:epic** identifier used within the SeraphID system:

```
did:epic:priv:b4eeeb80d20bfb38b23001d0659ce0c1d96be0aa
```

This identifier represents a specific self-sovereign identity on the EpicChain blockchain, showcasing the implementation and functionality of SeraphID.

### Build and Run

To build and run the SeraphID-SelfSovereign solution, follow these steps:

1. Build the project:
   ```sh
   make build
   ```

2. Run the project:
   ```sh
   make run
   ```

3. Test the implementation by making a GET request to retrieve the identifier details:
   ```sh
   curl -X GET http://localhost:8080/1.0/identifiers/did:epic:priv:b4eeeb80d20bfb38b23001d0659ce0c1d96be0aa
   ```

These commands will compile the solution, start the service, and allow you to query the details of the specified identifier.

### References

For additional information and resources related to the EpicChain platform and its components, please refer to the following links:

- [EpicChain Official Page](https://epic-chain.org)
- [EpicChain Demo Application on GitHub](https://github.com/epic-chain/epicchain-demo)
- [EpicChain Smart Contract Templates and Examples on GitHub](https://github.com/epicchainlabs/epicchain-smart-contracts)
- [EpicChain SDK on GitHub](https://github.com/epic-chain/epicchain-sdk)
- [EpicChain Chrome Extension on GitHub](https://github.com/epicchainlabs/epicchain-chrome-extension)
- [EpicChain DID Resolver on GitHub](https://github.com/epicchainlabs/epicchain-did-driver)

These resources provide further insights into EpicChain's features, tools, and extensions, helping you explore and utilize the full potential of the platform.

### License

SeraphID-SelfSovereign is distributed under the open-source [MIT License](https://github.com/epicchainlabs/seraph-Id-self-overeign/blob/master/LICENSE), allowing for broad usage and modification in compliance with open-source principles.